# AsyaFoodie

> A multi-Asian cuisine website featuring recipes, recommended restaurants in the Philippines, and a food guide for eating well while studying or under stress.

---

## About

AsyaFoodie is a static, multi-page website that celebrates dishes from across Asia. Visitors can browse iconic recipes, discover restaurants to visit around the Philippines, and explore food recommendations to help during stressful or study-heavy times.

## Features

- **Recipes**: step-by-step pages for iconic Asian dishes
- **Restaurant guide**: recommended local restaurants serving Asian cuisine
- **Food guide**: food recommendations for studying or stressful periods
- **Homepage carousel**: browse the Recipes, Restaurants, and Food Guide sections from the landing page
- **Responsive layout**: sticky navbar with a mobile hamburger menu, plus a footer with quick links

## Content

### Recipes

| Dish        | Page             |
| ----------- | ---------------- |
| Katsudon    | `katsudon.html`  |
| Adobo       | `adobo.html`     |
| Peking Duck | `peking.html`    |
| Pad Thai    | `padthai.html`   |
| Takoyaki    | `takoyaki.html`  |
| Turon       | `turon.html`     |
| Soju Mojito | `soju.html`      |
| Jasmine Tea | `jasminetea.html`|

### Restaurants

| Restaurant                     | Page          |
| ------------------------------ | ------------- |
| Toyo Eatery                    | `Toyo.html`   |
| Barbara's Heritage Restaurant  | `Barbara.html`|
| Lágrima San Juan               | `Juan.html`   |
| China Blue by Jereme Leung     | `China.html`  |

## Tech Stack

- HTML5, CSS3, and vanilla JavaScript
- [Bootstrap 5.3.5](https://getbootstrap.com/) (via CDN)
- [Bootstrap Icons 1.11.1](https://icons.getbootstrap.com/) (via CDN)

## Project Structure

```
asyafoodie/
├── index.html          # Landing page
├── recipe.html         # Recipe listing
├── restaurant.html     # Restaurant listing
├── foodguide.html.html # Food guide page
├── katsudon.html       # Individual recipe pages
├── adobo.html
├── peking.html
├── padthai.html
├── takoyaki.html
├── turon.html
├── soju.html
├── jasminetea.html
├── Toyo.html           # Individual restaurant pages
├── Barbara.html
├── Juan.html
├── China.html
├── Images/             # Site images
├── *.png               # Food guide images (Avocado, Congee, Miso, Pho, ...)
└── .vscode/            # Editor settings
```

## Getting Started

No build step is required.

1. **Clone the repository**
   ```bash
   git clone https://github.com/HiraiGinji/asyafoodie.git
   cd asyafoodie
   ```

2. **Open the site**
   - Double-click `index.html`, **or**
   - Serve it locally:
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000`.

> An internet connection is needed for the Bootstrap and Bootstrap Icons CDNs.
