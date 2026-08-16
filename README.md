# Younus Khan Portfolio

This is a one-page personal website designed to present a professional summary, key skills, experience highlights, and selected personal projects. The site is hosted on GitHub Pages and uses a custom domain registered through Name.com.

## Purpose

The website serves as a digital portfolio and professional landing page for Younus Khan. It introduces his background, areas of expertise, and personal work in AI, automation, business analysis, and digital strategy.

## What is included

- Professional profile and headline
- Contact details and social links
- Summary of core capabilities
- Featured project cards
- Experience overview
- Responsive design for desktop and mobile viewing

## Project structure

```text
.
├── index.html
├── style.css
├── README.md
├── headshot.jpg
└── .gitignore
```

## Local preview

Because this is a static site, you can preview it locally with any browser or by running a simple local web server.

From the project folder, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages hosting

This project is intended to be hosted using GitHub Pages.

Typical setup:

1. Push the repository to GitHub.
2. Open the repository settings.
3. Go to Pages.
4. Select the branch and root folder for publishing.
5. Save the settings. GitHub Pages will generate the live site URL.

## Custom domain setup

The website is configured to use a custom domain purchased from Name.com.

To connect a custom domain in GitHub Pages:

1. Add the domain in the GitHub Pages settings.
2. Create the required DNS records in Name.com.
3. Wait for DNS propagation.
4. Confirm the site loads correctly over the custom domain.

Typical DNS setup usually includes:

- A record or CNAME record for the root/apex domain
- Optional www forwarding or alias configuration

## Customization

To update the content, edit the text in the HTML file.

Common items to change:

- Name and title
- Email address
- GitHub and LinkedIn links
- Professional summary
- Skills and project descriptions
- Work experience entries

To update styling, edit the CSS file in the project root.

## Notes

This is a lightweight, no-framework website built for speed, simplicity, and easy deployment. It is well suited for a personal portfolio, professional profile, or personal brand landing page.
