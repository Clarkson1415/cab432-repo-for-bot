# Scooby's Cafe and Restaurant Website

## Features

- Online ordering
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

- **`index.html`** - landing page
- **`menu.html`** - the restaurant's menu
- **`order.html`** / **`onlineorder.html`** - online ordering flow, with supporting assets under `order-html/`, `order-css/`, and `order-js/`
- **`contact.html`** / **`contact-form.html`** - contact page and form
- **`feedback.html`** - customer feedback form
- **`login.html`** - a simple login page
- **`images/`** - site imagery (menu photos, banners, icons)

Styling is split across several page-specific style sheets (`main-style.css`, `menu.css`, `order.css`, `login.css`, `feedback.css`, `formStyle.css`, `pages-styles.css`) plus a bundled `bootstrap.css` for layout scaffolding. Interactive behavior (form handling, menu interactions, ordering logic) lives in `script.js` and the `order-js/` folder. There's no build step or package manager involved—it's a static website.

## Running it locally

There's nothing to install. Clone the repository and open `index.html` directly in a browser, or serve the folder with any static file server, for example:

```bash
python -m http.server 8080
```

Then visit <http://localhost:8080>.

## Attribution

The original restaurant website template and design are credited to [iamdulanga/restaurant-website](https://github.com/iamdulanga/restaurant-website).