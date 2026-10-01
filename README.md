# MyPortfolio

An early personal portfolio landing page for Ryan Carrasco, built with HTML and CSS. It introduces Ryan as a software engineer and provides direct links to his email, GitHub, and LinkedIn profiles.

## What's included

- A navigation bar with Ryan's name, section labels, and contact/social links.
- A full-screen hero section with his name and role over a background image.
- A small, dependency-free codebase: `index.html` and `index.css`.

## View locally

The stylesheet uses the root-relative path `/index.css`, so serve the folder locally rather than opening `index.html` directly as a file:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Project status

This repository is an initial landing-page prototype. The **About Me** and **Projects** labels do not yet link to sections, and the page does not currently include project cards or a résumé download. The hero and social images load from external URLs, so their appearance depends on those sites remaining available. The page has no build process or framework dependency.
