# Loopstack - Flower Website

A modern, animated single-page landing website with smooth animations and a sleek dark theme design.

## 🌐 Features

- Smooth CSS animations and transitions
- Responsive design
- Modern dark theme with green accent colors
- Gradient backgrounds and glassmorphism effects
- Custom typography using Google Fonts
- Interactive hover effects

## 🛠 Tech Stack

- **HTML5**
- **CSS3** (Custom animations, gradients, glassmorphism)
- **JavaScript** (GSAP for animations)
- **Google Fonts** (Outfit, Playfair Display, General Sans)

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/mugi-sha/flower-website.git
```

2. Navigate to the project directory:
```bash
cd flower-website
```

### Running the Project

Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📁 Project Structure

```
flower-website/
├── index.html          # Main HTML file
├── .gitignore          # Git ignore file
└── README.md           # Project documentation
```

## 🎨 Customization

### Colors
The theme uses CSS custom properties that can be easily modified:

```css
:root {
    --green: #39FF14;
    --line: rgba(255, 255, 255, 0.18);
    --muted-55: rgba(255, 255, 255, 0.55);
    --muted-45: rgba(255, 255, 255, 0.45);
    --divider: rgba(255, 255, 255, 0.2);
}
```

### Fonts
The project uses Google Fonts that can be changed in the `<head>` section of `index.html`.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 👤 Author

**Mugisha David** - [GitHub](https://github.com/mugi-sha)

## 📄 License

This project is open source and available under the MIT License.
