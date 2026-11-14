# Tandem Team Website

A responsive, three-page portfolio site for an independent creative team. It uses plain HTML, CSS, and JavaScript with no build step or package dependencies.

## Project structure

```text
team-website/
├── index.html        # Home page
├── projects.html     # Selected projects
├── contact.html      # Contact details and inquiry form
├── css/
│   └── styles.css    # Shared styles for every page
├── js/
│   └── script.js     # Shared navigation and form behavior
├── .gitattributes    # Consistent text-file line endings
└── README.md
```

## Preview

Open `index.html` in a browser. The pages can also be served with any static file server; no compilation is required.

The site loads its typefaces from Google Fonts and its sample photography from Unsplash, so those assets require an internet connection.

## Customize

- Replace the Tandem name, sample project copy, and contact details with your team's information.
- Update the contact address in `contact.html` wherever `hello@tandem.studio` appears. The form opens a prefilled email in the visitor's default email app; it does not submit to a server.
- Replace the remote image URLs in the HTML with your own photography.
- Adjust the shared colors, typography, and responsive layouts in `css/styles.css`.
