# Lamiya Rahman — Portfolio

A personal portfolio site showcasing my background in software development,
quality assurance, and cyber security — built with plain HTML, CSS, and
JavaScript (no build step, no dependencies).

**Live site:** _add your published GitHub Pages link here after deploying_

## Structure

```
.
├── index.html                  # Page markup
├── css/
│   └── style.css                # All styling
├── js/
│   └── script.js                 # Scroll-reveal animation
├── assets/
│   └── documents/
│       ├── One-Stop-Home-Management-Solutions-Project-Proposal.pdf
│       └── Parental-Supervision-Application-Software-Test-Plan.pdf
└── README.md
```

## Sections

- **Profile** — background and focus areas
- **Core Skills** — programming, QA/testing, and tooling
- **Cyber Security Training** — coursework from an ongoing Professional
  Diploma in Cyber Security
- **Project Case Files** — three featured projects, linking out to a GitHub
  repository and two downloadable PDF reports
- **Education** — academic timeline
- **Contact**

## Running locally

No build tools required — just open `index.html` in a browser, or serve the
folder locally:

```bash
# Python
python3 -m http.server 8000

# Node (if you have it)
npx serve .
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages

1. Push this folder to a GitHub repository (see steps below).
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the `main` branch and `/ (root)` folder, then **Save**.
5. GitHub will publish the site at `https://<username>.github.io/<repo-name>/`
   within a minute or two.

## License

Personal project — all content and documents belong to Lamiya Rahman.
