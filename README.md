# Sunshinee Technologies — Official Website

[![GitHub Pages Deployment](https://github.com/abishek-david/sunshinee-technologies-website/actions/workflows/static.yml/badge.svg)](https://github.com/abishek-david/sunshinee-technologies-website/actions/workflows/static.yml)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Website-sunshineetechnologies.co.in-0056b3.svg)](https://www.sunshineetechnologies.co.in)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Sunshinee Technologies is a premier IT consultancy, recruitment, training, and digital solutions provider founded in 2023 in Coimbatore, Tamil Nadu, India.

🌐 **Production Website**: [https://www.sunshineetechnologies.co.in](https://www.sunshineetechnologies.co.in)

---

## 🚀 Overview

This repository contains the complete frontend codebase for the official Sunshinee Technologies website, structured for optimal performance, responsive mobile-first layouts, and automated deployment via GitHub Pages.

### Included Pages & Modules
- **Home (`index.html`)**: Complete landing experience highlighting core consultancy pillars, structured methodology, client journey, interactive FAQ accordion, and interactive consultation scheduling.
- **About Us (`about.html`)**: Company founding background (2023), vision, mission, leadership principles, and strategic milestones.
- **Services (`services.html`)**: Detailed practice areas covering Technology Consulting, Business Strategy, Professional Advisory, Digital Solutions, Corporate Training, and Recruitment.
- **Contact Us (`contact.html`)**: Coimbatore headquarters coordinates, direct contact options, operational schedule, interactive Google Maps integration, and inquiry dispatch.
- **Privacy Policy (`privacy.html`)**: Comprehensive privacy documentation, data handling protocols, and terms of service.
- **404 Not Found (`404.html`)**: Custom branded error page for missing URLs with intuitive recovery navigation.

---

## 🛠️ Tech Stack & Architecture

- **Semantic HTML5**: Validated document hierarchy, Open Graph metadata, structured semantic tags, and accessible ARIA attributes.
- **Modern Vanilla CSS3**: Custom design token system (CSS custom properties), responsive flexbox and CSS grid layouts, smooth micro-interactions, and glassmorphic card styling.
- **JavaScript (ES6+)**: Zero-dependency interactive client scripts handling sticky navigation with scroll progress, mobile menu drawer, modal triggers, toast notifications, FAQ accordions, and client-side form validation.
- **Typography & Icons**: Google Fonts (Roboto) and FontAwesome 6 icon suite.
- **CI/CD**: GitHub Actions workflow deploying to GitHub Pages with custom domain binding.

---

## 📁 Repository Structure

```
sunshinee-technologies-website/
├── .github/
│   └── workflows/
│       └── static.yml           # Automated GitHub Pages CI/CD workflow
├── assets/
│   ├── css/
│   │   └── style.css            # Complete design system & responsive styling
│   ├── images/                  # High-resolution optimized brand & section media
│   │   ├── logo.png
│   │   ├── favicon.png
│   │   ├── hero-consulting.jpg
│   │   ├── about-consulting.jpg
│   │   ├── tech-consulting.jpg
│   │   ├── business-consulting.jpg
│   │   ├── professional-consulting.jpg
│   │   ├── digital-solutions.jpg
│   │   ├── training-development.jpg
│   │   ├── recruitment-workforce.jpg
│   │   ├── coimbatore-hub.jpg
│   │   └── journey-growth.jpg
│   └── js/
│       └── main.js              # Interactive UI controls, modals, and forms
├── .gitignore                   # Version control ignore definitions
├── 404.html                     # Custom 404 error page
├── about.html                   # About Us page
├── CNAME                        # Custom domain binding (www.sunshineetechnologies.co.in)
├── contact.html                 # Contact Us page
├── index.html                   # Main landing page
├── LICENSE                      # Apache 2.0 Open Source License
├── privacy.html                 # Privacy policy & terms
├── README.md                    # Project documentation
├── robots.txt                   # Search engine crawler instructions
├── services.html                # Services & practice areas page
└── sitemap.xml                  # XML sitemap for SEO indexing
```

---

## 💻 Local Development

To run and preview the website locally:

### Option 1: Python Built-in Server
```bash
# In the repository root directory:
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

### Option 2: Node / npx `serve`
```bash
npx serve .
```

### Option 3: VS Code / IDE
Install the **Live Server** extension and click **Go Live** on `index.html`.

---

## 🚀 Deployment

The site is configured with automated continuous deployment via GitHub Actions:
- Any push to the `main` branch triggers `.github/workflows/static.yml`.
- The static files are packaged and published to **GitHub Pages**.
- Traffic routes directly through the custom domain configured in `CNAME` (`www.sunshineetechnologies.co.in`).

---

## 📬 Contact & Inquiries

- **Organization**: Sunshinee Technologies
- **Email**: [bruno@sunshineetechnologies.co.in](mailto:bruno@sunshineetechnologies.co.in)
- **Location**: Coimbatore, Tamil Nadu, India
- **Operating Hours**: Monday – Friday: 9:00 AM – 6:00 PM IST | Saturday: 9:00 AM – 1:00 PM IST

---

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).
