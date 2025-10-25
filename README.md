# Dr. RD Hariparsad - Orthopaedic Surgeon Website

![Website Preview](assets/imgs/dr_hariparsad_logo.jpg)

## Overview
This is the official website for Dr. RD Hariparsad, a distinguished orthopaedic surgeon based in Durban, South Africa. The website showcases Dr. Hariparsad's professional services, qualifications, practice locations, and provides a platform for patients to get in touch.

## Repository Structure
```
├── index.html              # Main website page
├── thank-you.html         # Form submission confirmation page
├── CNAME                  # Custom domain configuration
├── robots.txt            # Search engine crawling rules
├── sitemap.xml          # Site structure for search engines
├── README.md            # Project documentation
├── .github/
│   └── workflows/      # GitHub Actions deployment configuration
│       └── static.yml
├── assets/
│   ├── icons/         # Service and UI icons
│   └── imgs/         # Website images and logos
└── css/
    └── style.css    # Main stylesheet
```

## Features
- **Responsive Design**: Mobile-first approach with adaptive layouts
- **Modern UI Components**:
  - Sticky navigation header
  - Animated hero section
  - Service cards with hover effects
  - Collapsible FAQ accordion
  - Interactive location maps
  - Contact form with FormSubmit integration
- **Performance Optimized**:
  - Loading animation
  - Lazy-loaded images
  - AOS scroll animations
  - Minified assets
- **SEO Implementation**:
  - Structured data (JSON-LD)
  - Meta tags optimization
  - XML sitemap
  - Robots.txt configuration
  - Custom domain setup

## Technologies Used
- HTML5 & CSS3
- Vanilla JavaScript
- External Libraries:
  - Bootstrap Icons 1.11.3
  - Font Awesome 6.0.0
  - Google Fonts (Poppins)
  - AOS 2.3.4 for animations
- GitHub Pages for hosting
- GitHub Actions for deployment

## Development Setup
1. Clone the repository
2. No build process required - static HTML/CSS/JS
3. Open `index.html` in a browser to view locally

## Deployment
The site is automatically deployed to GitHub Pages using GitHub Actions workflow:
- Pushes to `main` branch trigger deployment
- Configuration in `.github/workflows/static.yml`
- Custom domain setup via `CNAME` file

## SEO Configuration
- `robots.txt` allows all crawlers
- `sitemap.xml` includes all major sections
- Structured data for medical practice
- Meta tags optimized for medical services

## Contact Form Integration
- Uses FormSubmit service
- Redirects to `thank-you.html` on submission
- Sends notifications to ortho.gateway@gmail.com

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Credits
- Development: [Spectra Studios](https://spectrastudios.co.za)
- Icons: [Flaticon](https://www.flaticon.com/)
- Photos: Licensed to Dr. RD Hariparsad

## License
© 2025 Dr. RD Hariparsad. All rights reserved.
Website developed and maintained by Spectra Studios.
