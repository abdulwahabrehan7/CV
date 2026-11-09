# FORME — CV Maker Website

A responsive black-and-white CV builder made with HTML, Tailwind CSS and vanilla JavaScript.

## Run locally
1. Extract the ZIP.
2. Open the `cv_maker_website` folder in VS Code.
3. Open `index.html` with the Live Server extension (or double-click it in a browser).

## Features
- Four CV templates: Modern, Classic, Minimal and Executive
- Live preview while typing
- Personal details, profile photo, summary, experience, education, skills, languages, certifications, projects and additional information
- Add/remove repeatable experience, education and project entries
- A4 / US Letter page size and compact / standard / large text options
- Toggle photo, projects and certifications
- PDF export with a filename based on the CV owner's name
- Responsive editor and preview

## APIs / external libraries
No CV-data API key or backend is required. Your CV content is handled locally in the browser.
- Tailwind CSS CDN: styling
- html2pdf.js CDN: client-side PDF generation
- Lucide CDN: interface icons
- Google Fonts CDN: DM Sans / Playfair Display (fallback fonts are included)

An internet connection is needed to load the CDN libraries. The PDF is generated in your browser; CV data is not uploaded to a server.

## Notes
This is a front-end starter project. If you later want cloud saving, user accounts, AI writing suggestions or live job-description keyword matching, those require a backend or external service and should be added with appropriate privacy controls.
