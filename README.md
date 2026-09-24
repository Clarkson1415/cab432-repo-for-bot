# Scooby's Cafe and Restaurant Website

## Features
- Signup and login
- Feedback
- A menu of current items
- A homepage (index.html) with:
  - About Us Section
  - All Time Favourite
  - WE DELIVER section with an online order button
  - Opening Hours
  - Contact information and Opening Hours

## What's here
The site is a straightforward multi-page restaurant front end:

- **index.html** - landing page
- **menu.html** - the restaurant's menu
- **contact.html** / **contact-form.html** - contact page and form
- **feedback.html** - customer feedback form
- **login.html** - a simple login page
- **images/** - site imagery (menu photos, banners, icons)

Styling is split across several page-specific style sheets (<code>main-style.css</code>, <code>menu.css</code>, <code>login.css</code>, <code>feedback.css</code>, <code>formStyle.css</code>, <code>pages-styles.css</code>) plus a bundled <code>bootstrap.css</code> for layout scaffolding. Interactive behavior (form handling, menu interactions) lives in <code>script.js</code>. There's no build step or package manager involved—it's a static website.

## Running it locally
There's nothing to install. Clone the repository and open <code>index.html</code> directly in a browser, or serve the folder with any static file server, for example:

```bash
python -m http.server 8080
```

Then visit <a href="http://localhost:8080" rel="nofollow">http://localhost:8080</a>.

## Attribution
The original restaurant website template and design are credited to <a href="https://github.com/iamdulanga/restaurant-website">iamdulanga/restaurant-website</a>.