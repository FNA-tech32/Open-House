# Open-House

Open-House is a static landing page for a design-led estate agency. It presents current listings, past sales, press quotes, and a newsletter signup, and it adapts from a wide desktop layout down to a phone screen.

## What the page includes

- A fixed navigation bar with Buy, Sell, and Journey on the left, the **Open-House** name in the center, and Directory, Shop, About, and Subscribe on the right.
- A hero with a kitchen image, the story “Space Age: six space-saving London home,” and a Read More link.
- A press quote and a Sell With Us call to action.
- Featured sales: six homes with name, price, location, and tenure (freehold, leasehold, or share of freehold).
- A second quote and a home-valuation prompt.
- A seller testimonial beside a portrait.
- A short statement about the agency and an About Us link.
- Featured past sales marked as sold.
- A footer with About and Contact links, plus a newsletter form.

## Contact

These details appear in the footer:

- Phone: +44 20 3892 6140
- Email: hello@open-house.com
- Office: Clerkenwell, London EC1V
- Hours: Monday to Friday, 9:00–18:00

## How to view it

Open `index.html` in a browser. No build step is required; the page loads `style.css` directly.

To preview it from a local server:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Project structure

| File | Role |
| --- | --- |
| `index.html` | Page markup |
| `style.css` | Styles the browser uses, including desktop and mobile layouts |
| `style.scss` | Source stylesheet the CSS was compiled from |
| `favicon.ico` | Tab icon |

## Tech

HTML and CSS, with the stylesheet written in SCSS. Type is set with Montserrat and Rubik from Google Fonts. Layout uses flexbox and CSS grid, with a mobile layout for narrow screens.
