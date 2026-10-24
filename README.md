# Project-3: Tech Support Hub

A single-page, responsive website for "Tech Support Hub", a fictional IT support service.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-528DD7?style=flat-square&logo=fontawesome&logoColor=white)

## Overview

I built this site with a strong focus on user experience. The goal was an intuitive, easy-to-navigate page where visitors can quickly find what they need and contact the support team without hassle.

## Features

- **Sections:** hero, About, "Let the Numbers Talk" statistics, Why Choose Us, Our Services, Client Testimonials and Contact Us, reached through in-page links with smooth scrolling
- **Services:** Virus & Malware Removal, Network Setup, Data Backup & Recovery, Hardware Repair and Cloud Solutions
- **Animated counters:** the statistics count up when they scroll into view
- **Contact form:** collects name, email, phone, issue description and extra details, then opens the visitor's email app with a pre-filled message (`mailto:`), so no server is needed
- **Extras:** an embedded Google Map, a page preloader, a back-to-top button and a footer year set by script

## Tech Stack

- HTML, CSS and vanilla JavaScript
- Font Awesome 6.4 and bundled Lato web fonts
- The markup keeps Elementor and WPForms class names. All styles and scripts are local static files, with minified copies loaded by the page

## Getting Started

There is no build step. Open `index.html` in a browser, or serve the folder locally:

```bash
git clone https://github.com/4waiz/Project-3.git
cd Project-3
python -m http.server 8000   # then open http://localhost:8000
```

## Project Structure

```
Project-3/
├── index.html        # the whole site
├── favicon.ico
├── assets/
│   ├── css/          # main, fonts and preloader styles (+ .min.css)
│   ├── js/           # main.js (form, counters, preloader), frontend.js (+ .min.js)
│   └── webfonts/     # Lato and Font Awesome solid
└── media/            # logo, section backgrounds and testimonial photos
```

---

Built by [Awaiz Ahmed](https://github.com/4waiz)
