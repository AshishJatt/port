# Full Stack Web Development – Internship Project Collection

A GitHub-ready collection of front-end projects based on the work described in the internship report. The projects use **HTML5, CSS3 and vanilla JavaScript** and run directly in a modern browser.

## Projects

1. **Personal Portfolio Page** (`portfolio/`) – sticky navigation, hero section, project cards and responsive layout.
2. **Form Validation** (`form-validation/`) – validates full name, email address and password, then displays error or success feedback.
3. **TechStore Landing Page** (`techstore/`) – promotional hero and responsive product grid for a fictional electronics store. The cart interaction is demo-only; there is no checkout or payment processing.
4. **Multi-Section Portfolio** (`final-portfolio/`) – About, Education, Projects and Contact sections with a mobile navigation toggle and client-side form feedback.

The root `index.html` is a landing page that links to all four projects.

## Run locally

No installation or build tools are required.

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a modern browser.
4. Select a project from the project collection page.

For a local development server, you can use the **Live Server** extension in Visual Studio Code, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Technologies

- HTML5 – semantic page structure and forms
- CSS3 – Flexbox, CSS Grid, gradients, responsive media queries and transitions
- JavaScript – DOM manipulation, event handling and client-side validation

## Repository structure

```text
full-stack-web-development-project/
├── index.html
├── README.md
├── assets/
│   └── style.css
├── portfolio/
│   ├── index.html
│   └── style.css
├── form-validation/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── techstore/
│   ├── index.html
│   ├── style.css
│   └── script.js
└── final-portfolio/
    ├── index.html
    ├── style.css
    └── script.js
```

## Notes

- This is a front-end demonstration repository. It does not include a server, database, authentication system or payment gateway.
- The contact forms validate input in the browser only; they do not transmit or store submissions.
- Replace the sample profile text and education details with your own information before publishing if needed.

## Author

**Ashish**  
B.Tech – Computer Science and Business Systems  
USN: 24BTRCB005
