# North Star Bakery

The final version of a four-page website for North Star Bakery, a neighborhood bakery in Saint Paul,
built for the Sophia *Introduction to Web Development* final project (Touchstone 5).

Live site: https://chiefkeef-art.github.io/north-star-bakery-touchstone-5/

## Pages and files

- `index.html` - welcome, what we're known for, featured item of the week, hours and location
- `products.html` - breads, pastries, cakes and cookies with price ranges, a category filter and
  a pre-order list
- `about.html` - the bakery's story, behind-the-scenes video, sourcing and team
- `contact.html` - pre-order and inquiry form, location and hours
- `css/styles.css` - one shared, mobile-first stylesheet (Flexbox layout and media queries)
- `js/main.js` - pre-order list, category filter, form validation and localStorage
- `images/`, `media/` - client media assets provided by Sophia

## Features

- **Pre-order list:** add items from the Products page (or the featured cookie on the Home page),
  change quantities and see an estimated total. The list follows the visitor to the contact form.
- **Category filter:** show all products or one category at a time.
- **Form validation:** clear messages under each field for required fields, email format, phone
  format, item detail length and pickup dates (48 hours' notice, one week for cakes, closed Mondays).
- **localStorage:** remembers the pre-order list, the last category filter and, if the visitor opts
  in, their name and email.

Design system: 4 colors (cream `#FFF8F0`, brown `#6B3E26`, peach `#D88C5A`, charcoal `#2F2A26`)
and 2 font families (Lora for headings, Nunito for body text).
