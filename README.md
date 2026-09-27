# Contact Page

A magazine-style contact adaptive page built as a front-end practice project, focused on translating a design into a pixel-close layout using Bootstrap's utility classes, media queries and SASS.

## Live Demo
[View live site](https://jasurbek-olimjonov.github.io/food-market1/)

## Overview
This project recreates a full-page contact layout. The contact, inbox, and recipe sections are built using Bootstrap utilities and SASS. Responsive design is achieved through a combination of media queries and CSS Grid properties to adapt the layout across different screen sizes.

## Tech Stack & Approach
Built primarily with Bootstrap (flex and spacing utilities) to deepen hands-on experience with the framework. Custom SCSS handles the parts Bootstrap's utilities couldn't cleanly express — typography, sizing, and fine-grained positioning.

## What I Practiced
- Building responsive layouts with media queries
- Choosing between CSS Grid properties and media queries
- Managing text sizes by setting a base `font-size` on `:root` and using relative units

## Project Structure
```
food-market1/
├── assets/
│   ├── foods/
│   ├── images/
│   └── svg/
├── styles/
│   ├── sections/
│   ├── breakpoints/
│   ├── utils/
│   │   ├── _mixins.scss
│   │   ├── _utilities.scss
│   │   └── _variables.scss
│   ├── style.css
│   ├── style.css.map
│   └── style.scss
├── pages/
|   ├── blog_post_page/ `same with index.html structure`
|   ├── blog_list_page/
|   ├── contact_page/
|   ├── recipes_page/
├── LICENSE
├── README.md
└── index.html
```

## Getting Started
Clone the repo and open `index.html` in your browser — or, if you're editing the SASS:
```bash
git clone https://github.com/Jasurbek-Olimjonov/food-market1.git
cd food-market1
# compile SASS if using a live-sass-compiler or similar
```

## Author
**Jasurbek Olimjonov**
[GitHub](https://github.com/Jasurbek-Olimjonov)

## License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
