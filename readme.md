# Sushiman 🍣

A modern, animated landing page for a Japanese food delivery service, built with [Vite](https://vitejs.dev/) and vanilla JS.

# visit
[Sushiman](https://sushi-sheikh.netlify.app/)
-- made by Md. Ahad Sheikh

## Features

- Responsive, mobile-friendly layout
- Animated sections using [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
- Modular CSS with section-based organization
- Modern asset management (SVGs, PNGs)
- Easy to customize and extend

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd sushi
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Start the development server:**
   ```sh
   npm run dev
   ```
   Open [http://localhost:5173](http://localhost:5173) in your browser.

4. **Build for production:**
   ```sh
   npm run build
   ```

5. **Preview the production build:**
   ```sh
   npm run preview
   ```

## Project Structure

```
sushi/
├── assets/         # Images and SVGs
├── css/
│   ├── style.css   # Main CSS file (imports section styles)
│   └── sections/   # Section-specific CSS
├── js/
│   └── script.js   # Main JS (AOS init, data, etc.)
├── public/         # Static assets (favicon, etc.)
├── index.html      # Main HTML file
├── package.json    # Project metadata and scripts
└── readme.md       # This file
```

## Customization

- **Images:** Replace images in the `assets/` folder as needed.
- **Colors & Fonts:** Edit CSS variables in `css/style.css`.
- **Content:** Update text and structure in `index.html`.

## Dependencies

- [Vite](https://vitejs.dev/) - Fast frontend build tool
- [AOS](https://michalsnik.github.io/aos/) - Animate On Scroll library

## License

This project is for educational/demo purposes.

---

**Made with ❤️ for Japanese food lovers!**