# Flipping Card UI Design

A 3D flipping credit card UI built with HTML & CSS — hover to flip between the front (logo, chip, card number) and back (magnetic strip, signature) using CSS 3D transforms.

🔗 **Live Demo:** https://flip-card-ui-uzi.netlify.app/
💻 **Repository:** https://github.com/MuhammadUzairKhalid15/Flipping-Card-Ui-Uzi-Solutions

## ✨ Features

- 🔄 Smooth 3D flip animation on hover (`transform-style: preserve-3d`)
- 💳 Front face: logo, chip, card number, holder name
- 🔙 Back face: magnetic strip, signature strip, customer service info
- 🪟 Glassmorphism-style card (blurred, semi-transparent background)
- 🎨 Gradient background accents

## 🔧 Built With

- **HTML5**
- **CSS3** – 3D transforms, `backface-visibility`, `perspective`, `backdrop-filter`

## 📂 Project Structure

```
Flipping-Card-Ui-Uzi-Solutions/
├── index.html
├── style.css
└── images/
    ├── logo.png
    └── chip.png
```

## 🚀 Getting Started

1. Clone the repository
   ```
   git clone https://github.com/MuhammadUzairKhalid15/Flipping-Card-Ui-Uzi-Solutions.git
   ```
2. Open `index.html` in your browser, then hover over the card to see it flip.

## 💡 What I Practiced

- Using `perspective` and `transform-style: preserve-3d` for realistic 3D flips
- `backface-visibility: hidden` to hide the reverse side of each face
- `backdrop-filter: blur()` for a glassmorphism card effect
- Structuring front/back face content with absolute positioning

## 📬 Feedback

Feedback and suggestions are always welcome — feel free to open an issue or reach out on LinkedIn!
