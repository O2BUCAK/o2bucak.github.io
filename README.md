# O2BUCAK — Personal Website

Personal website and portfolio of **Ersin ÖZBUCAK**, built with plain HTML, CSS and JavaScript and hosted on GitHub Pages.

🌐 **Live website:** [https://ersinozbucak.tr](https://ersinozbucak.tr)

The site brings together professional experience, infrastructure and open-source interests, personal projects, certifications, and contact information.

## Features

- Responsive, single-page portfolio homepage
- Turkish and English language support
- Sections for personal introduction, Enterprise Reference Architecture, projects, certifications, professional experience, and current interests
- Dedicated contact and privacy policy pages
- Project, professional network, and GitHub links
- SEO metadata, canonical URL, Open Graph metadata, and structured data
- Google AdSense verification snippet included in the page headers

## Pages

| File | Description |
| --- | --- |
| `index.html` | Main portfolio and project overview |
| `contact.html` | Contact and professional links |
| `privacy.html` | Privacy policy |
| `CNAME` | Custom domain configuration for `ersinozbucak.tr` |

## Project Structure

```text
.
├── index.html
├── contact.html
├── privacy.html
├── CNAME
├── README.md
├── llms.txt
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    ├── documents/
    │   └── Ersin-Ozbucak-CV.pdf
    ├── images/
    │   └── ...
    └── favicon.svg
```

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages
- Google AdSense

No frontend framework, package manager, or build pipeline is required.

## Deployment

The repository is configured for **GitHub Pages** and uses the custom domain declared in the `CNAME` file.

To deploy:

1. Push changes to the `main` branch.
2. In the repository, open **Settings → Pages**.
3. Select `main` as the deployment branch if GitHub Pages is not already configured.
4. Ensure the custom domain is set to `ersinozbucak.tr` and DNS records point to GitHub Pages.

GitHub Pages publishes the static files directly; there is no build step.

## Local Preview

You can open `index.html` directly in a browser. For a local HTTP preview, run:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Notes

- Keep the `CNAME` file in the repository root to preserve the custom domain configuration.
- Update the privacy policy whenever the site's data collection or third-party services change.
- The AdSense snippet is installed for site verification. Ad serving remains subject to Google's review and approval.

## License

Unless otherwise stated, the website's original content, personal materials, and branding belong to Ersin ÖZBUCAK. Contact the owner before reusing them.
