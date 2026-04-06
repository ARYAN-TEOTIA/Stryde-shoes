# 👟 STRYDE — Premium Shoe E-Commerce Website

A fully responsive, modern e-commerce website for a premium footwear brand — built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies.

🔗 **Live Demo:** [https://aryan-teotia.github.io/Stryde-shoes/](https://aryan-teotia.github.io/Stryde-shoes/)

---

## 📸 Features

- **Hero Section** — Animated floating shoe with brand stats
- **Product Grid** — 8 shoe listings with category filtering (All / Running / Lifestyle / Sport)
- **Shopping Cart** — Slide-in drawer with add, remove, and quantity controls
- **Wishlist** — Toggle wishlist on any product
- **Live Toast Notifications** — Instant feedback on all actions
- **Newsletter Signup** — Email subscription with validation
- **Fully Responsive** — Works on mobile, tablet, and desktop
- **Marquee Strip** — Animated promo banner
- **Brand Showcase** — Featured brand logos section

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure & layout |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | Cart logic, filtering, interactivity |
| Google Fonts | Bebas Neue + DM Sans typography |
| GitHub Pages | Free hosting & deployment |

---

## 🚀 Getting Started Locally

1. Clone the repository:
```bash
git clone https://github.com/aryan-teotia/Stryde-shoes.git
```

2. Open the project folder:
```bash
cd Stryde-shoes
```

3. Open `index.html` in your browser — no build step needed!

---

## 📁 Project Structure

```
Stryde-shoes/
│
├── index.html        # Main website file (all-in-one)
└── README.md         # Project documentation
```

---

## 🎨 Design Highlights

- Dark luxury aesthetic with a bold red accent (`#c8372d`)
- **Bebas Neue** display font for headlines
- **DM Sans** for body text — clean and modern
- CSS keyframe animations for the floating hero shoe
- Smooth cart drawer transition with backdrop overlay
- Hover micro-interactions on all product cards

---

## 📱 Responsive Breakpoints

| Screen | Layout |
|---|---|
| Desktop (1100px+) | 4-column product grid |
| Tablet (900px) | 2-column grid, hidden nav links |
| Mobile (600px) | Single column, full-width cart |

---

## 🔧 Customisation

To add your own products, edit the `products` array in the `<script>` section of `index.html`:

```javascript
const products = [
  {
    id: 9,
    name: 'Your Shoe Name',
    brand: 'Brand',
    price: 5999,
    oldPrice: 7999,   // set null if no discount
    badge: 'New',     // 'New', 'Sale', 'Limited', or null
    category: 'running', // 'running', 'lifestyle', or 'sport'
    colors: ['#fff', '#000'],
    imgColor: '#3a7bd5'
  }
];
```

---

## 🌐 Deployment

This site is deployed using **GitHub Pages** for free.

To deploy your own fork:
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to **main branch**
4. Your site will be live at `https://yourusername.github.io/Stryde-shoes/`

---

## 👤 Author

**Aryan Teotia**
- GitHub: [@aryan-teotia](https://github.com/aryan-teotia)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
