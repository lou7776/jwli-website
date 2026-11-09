# JWLI Website

A static, responsive landing page for the Japanese Women's Leadership Initiative (JWLI), a Boston-based program that brings emerging women leaders from Japan to the U.S. for nonprofit management and leadership training. I built this as a front-end project to practice layout with Flexbox and responsive design.

<img width="1159" height="604" alt="Screenshot 2026-11-09 at 1 31 16 AM" src="https://github.com/user-attachments/assets/91aac18b-23c2-46cf-baa2-d0ed23a50edc" />


## What's on the page

- **Header and nav**: links to Home, Program, JWLIA, Fellows, News, Contact, and a Japanese language link, plus an Apply button
- **Hero**: logo, headline, short mission statement, and an email signup for when applications reopen
- **Mission section**: two highlighted goals with a pink top border
- **Our History**: the story of how JWLI started, with two images on the side
- **Who We Are**: profile of the founder, plus cards for the Fish Family Foundation and Simmons College
- **Newsletter signup**
- **Footer**: copyright, social links, and four columns of site links

## Built with

- HTML5
- CSS3 (Flexbox, media queries)
- [Font Awesome](https://fontawesome.com/) for the burger menu icon

No frameworks, no build step.

## Running it

1. Download or clone the project.
2. Make sure the `css/` and `img/` folders sit next to `index.html`.
3. Open `index.html` in your browser.

The Font Awesome icon loads from a kit script, so you need an internet connection for the burger icon to show.

## Responsive behavior

| Screen width | What changes |
| --- | --- |
| 768px and below | Nav links hide and the burger icon shows. Hero, history, and "Who We Are" sections stack in one column. The hero image is hidden. Footer sections stack. |
| 480px and below | Smaller image heights. Footer links stack and center. |
