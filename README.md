# acstartup.dev

My personal portfolio website built with Tailwind CSS showcasing projects, experience, and contact information.

## Features
- Custom Geist Sans typography for modern aesthetic
- Smooth hover animations and transitions
- Multi-page navigation (Home, Projects, Experience, Contacts)
- Circular profile image with proper image cropping
- Social media integration (LinkedIn, GitHub, X/Twitter)
- Active page subheader highlighting in navigation
- Project showcase with GitHub repository links

## Live Demo
🌐 [acstartup.dev](https://acstartup.dev)

## How to Run Locally

### Prerequisites
- Node.js installed on your machine
- npm package manager

### Installation & Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/acstartup/acstartup.dev.git
   cd acstartup.dev
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run development server**
   ```bash
   npm run dev
   ```
   This will start Tailwind CSS in watch mode, automatically rebuilding styles when you make changes.

4. **Open in browser**
   - Open `index.html` in your web browser
   - Or use a local server like Live Server (VS Code extension)

### Production Build

```bash
npm run build
```
Compiles and minifies Tailwind CSS for production deployment.

## File Structure
```
acstartup.dev/
├── index.html                    # Home page with bio and profile
├── projects/
│   └── index.html               # Projects showcase page
├── experience/
│   └── index.html               # Professional experience page
├── contact/
│   └── index.html               # Contact information page
├── files/                        # Images and assets
│   ├── main.png                 # Background image
│   ├── aura.jpg                 # Profile picture
│   ├── acstartup.dev.fill.png  # Logo
│   ├── github.png               # GitHub icon
│   ├── linkedin.png             # LinkedIn icon
│   └── x.png                    # X/Twitter icon
├── src/
│   └── input.css                # Tailwind CSS source
├── dist/
│   └── output.css               # Compiled Tailwind CSS
├── styles.css                    # Custom styles (Geist Sans font)
├── package.json                  # Dependencies and scripts
├── vercel.json                   # Vercel deployment config
└── README.md                     # This file
```

## Tech Stack
- **HTML** - Semantic markup and structure
- **CSS (Tailwind CSS v4)** - Utility-first styling
- **Geist Sans** - Modern typography from Vercel
- **Vercel** - Hosting and deployment platform
- **Git/GitHub** - Version control

## What I Learned
- Handling `img`s
- Utilizing `z-score`
- Cardinal directions `top-, bottom-, left-, right-` for adjustings
- `justify-between` and `items-baseline` for different texts on same line
- `italics` and `underline`
- using `geist-sans` font with `font-light, font-semibold, etc...`
- `lg:` for tailwindcss large graphics (desktop, laptop, etc...) only, must have a normal `top-20` and then a `lg: top-80` for MOBILE
- `text-base` is `medium` in tailwindcss

## Available Scripts

### `npm run dev`
Runs Tailwind CSS in watch mode for development. Automatically rebuilds `dist/output.css` when changes are detected in HTML or CSS files.

### `npm run build`
Compiles and minifies Tailwind CSS for production deployment. Outputs optimized CSS to `dist/output.css`.

### `npm install`
Installs all dependencies including Tailwind CSS v4, PostCSS, and Autoprefixer.

## Deployment

This site is deployed on **Vercel** with automatic deployments from the `main` branch.

### Deployment Configuration
- Framework Preset: Other
- Build Command: `npm run build`
- Output Directory: `.` (root)
- Install Command: `npm install`

### Manual Deployment
1. Push changes to GitHub `main` branch
2. Vercel automatically triggers a new build
3. Check deployment status in Vercel dashboard
4. Clear browser cache with `Cmd+Shift+R` to see updates

## Future Improvements
- Add Experience page content with timeline
- Create Contact page with email form
- Implement responsive mobile navigation menu
- Add more projects to Projects page
- Create blog section for technical writing
- Add dark/light mode toggle
- Implement smooth scroll animations
- Add loading animations for page transitions
- Optimize images with WebP format
- Add SEO meta tags and Open Graph images
- Implement Google Analytics for visitor tracking

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License
MIT License - feel free to use this as a template for your own portfolio!

## Contact
- **Website**: [acstartup.dev](https://acstartup.dev)
- **GitHub**: [@acstartup](https://github.com/acstartup)
- **LinkedIn**: [linkedin.com/in/acstartup](https://www.linkedin.com/in/acstartup/)
- **Twitter/X**: [@aidencstartup](https://x.com/aidencstartup)

---

Built with 💻 by Aiden Chen | Hosted on GitHub Pages via Vercel
