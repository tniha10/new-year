# New Year Offer Landing Page

New Year Offer is a desktop landing page built to promote a New Year sale. It brings together everything a seasonal campaign needs on a single page: an eye-catching banner, a headline discount, details of a midnight party event, a preview of upcoming offers, a showcase of gift products, and a newsletter signup.

The page uses a bold red, white and dark color palette with festive imagery, so the main offer and the calls to action stand out. It was built with plain HTML and CSS to practice turning a visual design into clean, readable code, including precise spacing, typography, gradients, rounded corners and layered images.

## Technologies Used

- **HTML5** for the page structure
- **CSS3** for styling, with Flexbox and Grid for layout
- **Google Fonts**: Inter and Merriweather

No JavaScript and no frameworks.

## Project Structure

```
new-year-offer-resources/
├── index.html      # page markup
├── styles.css      # all styling
├── images/         # banners, photos and illustrations
└── icons/          # footer icons (call, website, social)
```

## Sections

1. **Banner**: "New Year Party Celebration" over a fireworks image
2. **65% OFF**: sale headline with a "Happy New Year" image
3. **Midnight Party**: text, button and a 2024 ornament on a party photo
4. **Event Details**: place, date and time with a Join Now button
5. **Coming Soon**: text, a circular photo and a 2024 offer note
6. **Holidays Sale 50%**: gift box image with a 50% discount badge
7. **Portfolio**: a 3 x 2 grid of product images
8. **Newsletter**: email input and Subscribe button
9. **Footer**: address, contact details, social icons and copyright

## Design Details

| Item | Value |
| --- | --- |
| Design width | 1600px |
| Content width | 1320px (centered) |
| Gap between sections | 120px |
| Red | `#ff0000` |
| Dark | `#070211` |
| Heading font | Merriweather (400, 900) |
| Body font | Inter (400, 500, 600, 700) |

## CSS Techniques

- A `.container` class keeps the content 1320px wide and centered
- Flexbox for the banner, party, coming soon, newsletter form and footer rows
- CSS Grid for the portfolio images
- `linear-gradient` overlays on the banner and party backgrounds
- `border-radius` for rounded cards, the circular photo and the pill-shaped input
- `position: absolute` only where images overlap (gift box, red bar and discount badge)
- Reusable classes: `.label`, `.heading`, `.para`, `.btn`



- The layout is built for desktop screens (about 1600px wide) and is not responsive.
- All images come from the exported assets in the resources repo.
