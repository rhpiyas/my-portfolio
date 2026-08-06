# My Portfolio Website

A responsive personal portfolio website built with HTML, CSS, JavaScript, and Bootstrap.

This project presents:
- About, skills, and resume sections
- Project showcase with category filtering
- Achievements section
- Contact form with FormSubmit integration
- Dedicated thank-you page after message submission
- Dark mode toggle with local preference saving

## Live Site

- Production: https://rhpiyas.vercel.app/

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5
- AOS (Animate On Scroll)
- GLightbox
- Isotope
- Swiper
- Typed.js
- PureCounter

## Project Structure

```text
my-portfolio/
├── index.html
├── thank-you.html
├── count-me.html
├── diu-info-corner.html
├── face-entry-pro.html
├── smart-parking-system.html
├── starter-page.html
├── assets/
│   ├── css/
│   │   └── main.css
│   ├── js/
│   │   └── main.js
│   ├── img/
│   │   ├── achievements/
│   │   └── portfolio/
│   └── vendor/
└── Readme.txt
```

## Run Locally

Because this is a static site, no build step is required.

1. Clone the repository.
2. Open the project folder in VS Code.
3. Start a local server from the project root.

Using Python:

```bash
python3 -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

You can also use the VS Code Live Server extension.

## Contact Form Setup

The contact form in index.html is configured with FormSubmit:

- Action URL sends messages to: rakibhasanpiyas97@gmail.com
- `_next` redirects users to the thank-you page after successful submission

If you want to reuse this project, update these hidden fields in `index.html`:

- Form `action`
- `_subject`
- `_next`

## Customization Guide

- Personal info and section content: edit `index.html`
- Styling and theme variables: edit `assets/css/main.css`
- UI behavior and animations: edit `assets/js/main.js`
- Project details pages: edit each project HTML file

## Deployment

This project is ready for static hosting platforms such as:
- Vercel
- Netlify
- GitHub Pages

For Vercel, import the repository and deploy with default static settings.

## Credits

- Base template: iPortfolio by BootstrapMade
- Template details and license are preserved in `Readme.txt`

## License

This repository contains custom content built on top of the iPortfolio template.
Please review the template licensing terms before redistribution.