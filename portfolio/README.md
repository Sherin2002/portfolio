# Professional UI/UX Designer Portfolio

A modern, responsive portfolio website designed for UI/UX designers to showcase their work and skills.

## Features

- **Modern Design**: Clean, professional design with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Enhanced navigation with smooth scroll effects
- **Interactive Elements**: Animated skill bars, project cards, and statistics
- **Contact Form**: Ready-to-use contact form (backend integration needed)
- **Performance Optimized**: Lightweight and fast-loading

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction and key statistics
3. **Skills**: Showcase of design skills, tools, and research capabilities
4. **Projects**: Portfolio of featured work with case study links
5. **Contact**: Contact information and message form

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- Optional: A local web server for development

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies required.

### For Local Development

If you want to run a local server (recommended):

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Customization

### Personal Information

1. **Name and Title**: Update in `index.html`:
   - Line 12: Update `<title>` tag
   - Line 30: Update "Your Name" in the hero section
   - Line 31: Update "UI/UX Designer" if needed

2. **About Section**: 
   - Lines 70-80: Update the about text with your own story
   - Lines 85-95: Update statistics (projects, years, clients)

3. **Contact Information**:
   - Lines 250-280: Update email, LinkedIn, Dribbble, and Behance links
   - Replace `your.email@example.com` with your actual email
   - Update social media profile URLs

### Projects

Update the project cards in the Projects section (lines 180-250):
- Replace project images (currently placeholders)
- Update project titles, descriptions, and categories
- Add your actual case study links
- Modify project tags as needed

### Skills

Customize your skills in the Skills section (lines 120-170):
- Update skill names and proficiency percentages
- Modify tools list
- Adjust research capabilities

### Colors

The color scheme can be customized in `styles.css`:
- Lines 4-14: CSS variables for colors
- Primary: `#667eea` (purple-blue)
- Secondary: `#764ba2` (purple)
- Modify these values to match your brand

### Fonts

The portfolio uses Google Fonts (Inter). To change:
1. Update the font link in `index.html` (line 10)
2. Update `font-family` in `styles.css` (line 25)

## Adding Your Own Images

1. Create an `images` folder in the project root
2. Add your project images and profile photo
3. Update image paths in `index.html`:
   - Replace the SVG placeholder in the hero section (line 40)
   - Replace project placeholders with actual images

Example:
```html
<img src="images/project1.jpg" alt="Project 1">
```

## Contact Form

The contact form is currently set up with client-side validation. To make it functional:

1. **Option 1 - Form Submission Service**:
   - Use services like Formspree, Netlify Forms, or EmailJS
   - Update the form action in `index.html`

2. **Option 2 - Backend Integration**:
   - Create a backend endpoint to handle form submissions
   - Update the form submission handler in `script.js` (line 100)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. Optimize images before adding them (use tools like TinyPNG)
2. Consider lazy loading for project images
3. Minify CSS and JavaScript for production
4. Use a CDN for faster font loading

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch and folder
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to Netlify
2. Or connect your GitHub repository
3. Your site will be live instantly

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## License

This portfolio template is free to use for personal and commercial projects.

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Design: Modern UI/UX principles

## Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

---

**Good luck with your UI/UX design career! 🎨**

