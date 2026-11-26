# The Revive Fitness – Gym Website

Official website for **The Revive Fitness**, a unisex gym in Mango, Jamshedpur, Jharkhand, India.

A fast, mobile-friendly, single-page website built with plain HTML, CSS and JavaScript. There is no framework, no build step and no dependencies to install.

## Features

- Responsive design for phones, tablets and desktops, with a mobile menu
- Automatic light and dark mode
- Hero section with real gym photos
- About, Services and Membership (Monthly, Quarterly, Yearly) sections
- Batch timings table
- Photo gallery with tap-to-enlarge view
- Rotating motivational quotes
- Enquiry form that sends a ready-made message to WhatsApp or email
- Click-to-call button, floating WhatsApp button and Google Maps link
- Links to the gym's Instagram page: [@the_revivefitness](https://www.instagram.com/the_revivefitness/)

## Project structure

```
.
├── index.html   # The whole website (HTML, CSS, JS and photos)
└── README.md
```

> The photos are embedded inside the HTML file as base64 data, so the site works as a single file. If you add the file from this project, rename `revive-fitness.html` to `index.html`.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in any web browser.

Optional, using a local server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy for free on GitHub Pages

1. Push `index.html` to the `main` branch of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two, the site is live at `https://<your-username>.github.io/<repository-name>/`.

Other free hosts such as Netlify and Cloudflare Pages also work. Just upload the file.

## Customize

Open `index.html` in a code editor and use search (Ctrl+F) to find these items.

| What to change | Search for |
| --- | --- |
| Phone number | `7488533823` |
| Email address | `sk7488533@gmail.com` |
| Google Maps link | `maps.app.goo.gl` |
| Address text | `Mango, Dimna Road, Jamshedpur` |
| Instagram link | `the_revivefitness` |
| Membership plans and prices | `id="plans"` |
| Batch timings | `id="schedule"` |
| Motivational quotes | `var Q=[` |
| Colors | `--accent` (near the top of the `<style>` block) |

### Replacing the photos

Photos are inside `<img src="data:image/jpeg;base64,...">` tags. To use normal image files instead:

1. Create an `images/` folder and add your photos.
2. Replace each long `src="data:image/..."` value with a path such as `src="images/gym-1.jpg"`.

This also makes the HTML file much smaller and easier to edit.

## Contact form

The form has no server. When a visitor submits it, their message opens in WhatsApp (to the gym's number) or in their email app, ready to send. No visitor data is stored.

## Tech

- HTML5, CSS3, vanilla JavaScript
- Fonts: [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) and [Inter](https://fonts.google.com/specimen/Inter) from Google Fonts

## Contact

**The Revive Fitness**
Contact person: Santosh Kumar
Phone / WhatsApp: [+91 74885 33823](tel:+917488533823)
Email: [sk7488533@gmail.com](mailto:sk7488533@gmail.com)
Location: [Google Maps](https://maps.app.goo.gl/jJboCEz4xDE16y4S7)

## License

© The Revive Fitness. All rights reserved. The gym photos and branding belong to The Revive Fitness and may not be reused without permission.
