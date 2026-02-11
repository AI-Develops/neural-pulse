# Neural Pulse 🧠⚡

> A real-time AI activity monitoring dashboard featuring dynamic visualizations, brutalist design aesthetics, and live metrics tracking across multiple AI domains.

[![Live Demo](https://img.shields.io/badge/demo-live-00ff88?style=flat-square)](https://ai-develops.github.io/neural-pulse/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🎯 Overview

Neural Pulse is a cutting-edge web interface designed to visualize AI infrastructure metrics in real-time. Built with modern web technologies and a bold brutalist aesthetic, it provides an immersive monitoring experience for AI systems.

## ✨ Features

- **Real-time Metrics**: Live updating statistics for inference rates, GPU clusters, and latency
- **Interactive Charts**: Dynamic visualizations powered by Chart.js
- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern CSS3**: Utilizes advanced CSS features including:
  - CSS Custom Properties (Variables)
  - CSS Grid & Flexbox
  - CSS Animations & Transitions
  - Backdrop filters
  - Custom scrollbars
- **Brutalist Aesthetic**: Bold, distinctive design with neon accents and monospace typography
- **Domain Tracking**: Monitor activity across NLP, Vision, and Audio AI domains
- **Accessibility**: Respects prefers-reduced-motion for users with motion sensitivity

## 🛠️ Technologies

- **HTML5**: Semantic markup with modern elements
- **CSS3**: Advanced styling with custom properties and animations
- **JavaScript**: Vanilla JS for interactivity and animations
- **Chart.js**: Professional charting library for data visualization
- **Heroicons**: Beautiful hand-crafted SVG icons

## 📁 Project Structure

```
neural-pulse/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with modern CSS3
├── README.md           # Project documentation
└── repo-description    # GitHub repository description
```

## 🎨 Design Features

### Color Palette
- **Primary Background**: `#0a0a0a` (Deep black)
- **Accent Primary**: `#00ff88` (Neon green)
- **Accent Secondary**: `#ff006e` (Hot pink)
- **Accent Tertiary**: `#8b5cf6` (Purple)

### Typography
- **Display Font**: Courier New, monospace
- **Body Font**: Menlo, Monaco, Consolas, monospace

### Key CSS Features
- Animated grid background
- Pulsing status indicators
- Staggered card animations
- Gradient accents
- Custom scrollbar styling
- Hover state transformations

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/AI-Develops/neural-pulse.git
cd neural-pulse
```

2. Open `index.html` in your browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### GitHub Pages Deployment

This site is automatically deployed via GitHub Pages. Any push to the `main` branch will update the live site.

**Live URL**: `https://ai-develops.github.io/neural-pulse/`

## 📊 Metrics Displayed

- **Inference Rate**: Real-time requests per second
- **GPU Clusters**: Active node count and capacity
- **Average Latency**: Response time in milliseconds
- **Activity Timeline**: 24-hour request visualization
- **Model Distribution**: Breakdown by architecture type
- **Domain Activity**: NLP, Vision, and Audio task tracking

## 🎭 Customization

### Changing Colors

Edit the CSS custom properties in `style.css`:

```css
:root {
    --color-accent-primary: #00ff88;  /* Change primary accent */
    --color-accent-secondary: #ff006e; /* Change secondary accent */
    /* ... more variables */
}
```

### Updating Metrics

Modify the JavaScript in `index.html` to connect to real data sources:

```javascript
// Update the animateNumber function with live data
animateNumber(document.getElementById('inferenceRate'), yourLiveData);
```

## 🌟 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

**AI-Develops Organization**
- GitHub: [@AI-Develops](https://github.com/AI-Develops)

---

<div align="center">
Made with ⚡ by AI-Develops
</div>
