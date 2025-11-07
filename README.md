# CHGMF - Caring Hearts Global Mission Foundation

A professional, static website for the Caring Hearts Global Mission Foundation charitable organization.

## About

This is a modern, responsive static website designed for a charitable organization focused on serving communities in need worldwide. The website showcases the foundation's mission, programs, events, and ways to get involved.

## Features

- **Responsive Design**: Mobile-first approach ensuring great user experience on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations and intuitive navigation
- **Accessibility**: Built with accessibility best practices in mind
- **Performance**: Optimized for fast loading times with vanilla JavaScript (no heavy frameworks)
- **SEO Friendly**: Semantic HTML5 with proper meta tags

## Pages

1. **Home** (`index.html`) - Hero section, mission statement, featured programs, impact statistics, and testimonials
2. **About** (`about.html`) - Mission, vision, story, core values, leadership team, and impact statistics
3. **Programs** (`programs.html`) - Detailed information about four main programs: Food Security, Education Access, Healthcare Support, and Sustainable Development
4. **Events** (`events.html`) - Upcoming events and past event highlights
5. **Ways to Give** (`give.html`) - Donation options, volunteer opportunities, and impact of contributions
6. **Testimonials** (`testimonials.html`) - Stories from beneficiaries, donors, and volunteers
7. **Contact Us** (`contact.html`) - Contact information, form, office hours, FAQ, and map

## Technology Stack

- **HTML5**: Semantic markup for better SEO and accessibility
- **CSS3**: Modern styling with CSS variables, flexbox, and grid
- **Vanilla JavaScript**: Interactive features without dependencies
- **GitHub Pages**: Free, reliable hosting

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/campbellsinvestment/CHGMF.git
   cd CHGMF
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

### GitHub Pages Deployment

This site is configured for GitHub Pages. To deploy:

1. Go to your repository Settings > Pages
2. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/create-static-website-caring-hearts`)
3. Click "Save"
4. Your site will be published at `https://campbellsinvestment.github.io/CHGMF/`

## Project Structure

```
CHGMF/
├── index.html              # Homepage
├── about.html              # About page
├── programs.html           # Programs page
├── events.html             # Events page
├── give.html               # Ways to Give page
├── testimonials.html       # Testimonials page
├── contact.html            # Contact page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # JavaScript functionality
├── assets/
│   └── favicon.png         # Favicon (placeholder)
├── .nojekyll              # GitHub Pages configuration
└── README.md              # This file
```

## Customization

### Colors

The color scheme can be easily customized by modifying the CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #e74c3c;    /* Main brand color */
    --secondary-color: #3498db;  /* Secondary accent */
    --accent-color: #f39c12;     /* Accent highlights */
    /* ... more variables */
}
```

### Content

All content is directly in the HTML files and can be edited to match your organization's information:
- Update text, images, and links in each `.html` file
- Modify contact information in the footer
- Add your organization's social media links

### Forms

The contact form currently uses client-side validation. To make it functional:
1. Set up a form backend (e.g., Formspree, Netlify Forms, or custom API)
2. Update the form action in `contact.html`
3. Configure server-side validation and email notifications

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Copyright © 2024 Caring Hearts Global Mission Foundation. All rights reserved.

## Contact

For questions or support regarding this website, please visit the [Contact Us](contact.html) page.
