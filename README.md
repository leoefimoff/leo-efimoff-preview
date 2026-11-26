# Leo Efimoff

Source of the portfolio site for Leo Efimoff, a sculptor working with objects for interiors.

Live site: **https://leoefimoff.com**

Contact: leo@leoefimoff.com · Instagram: [@leoefimoff](https://www.instagram.com/leoefimoff/)

## Structure

Static site, no build step: plain HTML, CSS and JavaScript.

- `index.html`: the gallery and its full-screen view, plus the EN/ES interface text.
- `about.html`: biography and studio photos.
- `contacts.html`: contact form, email and Instagram.
- `works.js`: the list of works in display order. One entry per work; works photographed from several angles carry a `shots` array, its first frame being the cover.
- `images/`: three WebP sizes per frame (`-360`, `-720` and the 1440px original).

## Local preview

    python3 -m http.server 8800

Then open http://localhost:8800/.
