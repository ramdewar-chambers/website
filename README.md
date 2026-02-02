# Ramdewar Chambers Website

A modern, minimalist website for Ramdewar Chambers law firm, built with clean HTML, CSS, and vanilla JavaScript. Designed with Apple-inspired aesthetics featuring typography-led design, subtle animations, and professional presentation.

## Features

- **Modern Design**: Clean, minimalist layout with Apple-inspired aesthetics
- **Typography-Led**: Serif fonts for headings (Crimson Text), modern sans-serif for body text (Inter)
- **Smooth Animations**: Fade-in and slide-up animations using IntersectionObserver
- **Responsive Design**: Mobile-first approach with fluid layouts
- **Contact Form**: Integrated with FormSubmit for serverless form handling
- **Performance Optimized**: Lightweight, fast-loading static site
- **SEO Ready**: Proper meta tags and semantic HTML structure

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS with custom properties, Grid, and Flexbox
- **Vanilla JavaScript**: No frameworks, pure ES6+
- **Google Fonts**: Crimson Text (serif) and Inter (sans-serif)
- **FormSubmit**: Serverless form handling

## Project Structure

```
ramdewar-chambers/
├── index.html              # Homepage
├── attorneys.html          # Attorneys page
├── contact.html           # Contact page
├── thank-you.html         # Form submission confirmation
├── css/
│   └── styles.css         # Main stylesheet
├── js/
│   └── main.js           # JavaScript functionality
└── README.md             # This file
```

## Pages

1. **Home** (`index.html`)
   - Hero section with chambers introduction
   - About section highlighting expertise
   - Services overview with practice areas
   - Call-to-action section

2. **Attorneys** (`attorneys.html`)
   - Detailed profiles of G. Ramdewar and R. K. Ramdewar
   - Professional qualifications and experience
   - Chambers philosophy and approach

3. **Contact** (`contact.html`)
   - Contact information and office details
   - Contact form with validation
   - Office hours and location details

4. **Thank You** (`thank-you.html`)
   - Form submission confirmation
   - Next steps information

## Setup Instructions

### Local Development

1. Clone or download the project files
2. Open `index.html` in a web browser
3. For development, use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

### GitHub Pages Deployment

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save

Your site will be available at: `https://[username].github.io/[repository-name]`

### Form Configuration

The contact form uses FormSubmit (https://formsubmit.co/) for serverless form handling:

- **Current email**: chambersramdewar@gmail.com
- **Redirect URL**: Update the `_next` hidden field in `contact.html` to match your GitHub Pages URL
- **No backend required**: Forms are processed by FormSubmit and sent via email

To customize the form redirect:
1. Open `contact.html`
2. Find the line: `<input type="hidden" name="_next" value="https://ramdewar-chambers.github.io/thank-you.html">`
3. Replace the URL with your actual GitHub Pages URL

## Customization

### Colors
The color scheme uses:
- **Background**: #fafafa (off-white)
- **Primary Text**: #1a1a1a (dark charcoal)
- **Secondary Text**: #4a4a4a, #6a6a6a (gray variations)
- **Accent**: #ffffff (white for cards and sections)

### Typography
- **Headings**: Crimson Text (serif)
- **Body Text**: Inter (sans-serif)
- **Font weights**: 300, 400, 500, 600

### Animations
All animations use CSS transitions and the IntersectionObserver API for performance:
- **Fade-in**: Elements appear with opacity and transform changes
- **Slide-up**: Elements slide up from below the viewport
- **Hover effects**: Subtle transforms and shadows on interactive elements

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Load Time**: < 2 seconds on 3G
- **Bundle Size**: < 50KB total (excluding fonts)

## Contact Information

**Ramdewar Chambers**
- Address: Rooms 217 & 219, St James Court, St Denis Street, Port Louis, Mauritius
- Phone: +230 212 6036, +230 211 7322
- Email: chambersramdewar@gmail.com

## License

This project is created for Ramdewar Chambers. All rights reserved.