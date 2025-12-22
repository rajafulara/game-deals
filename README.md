# 🎮 Game Deals - Ultimate Global Price Tracker
Game Deals is a fully functional, single-file web application that tracks real-time PC game prices across 25+ global digital marketplaces (Steam, Epic Games, GOG, GreenManGaming, etc.).
Built with React, Tailwind CSS, and Babel directly in the browser, it requires no build step, no Node.js, and no server setup. Just download and run.

# ✨ Key Features
 * 🔥 Live Deal Feed: Real-time fetching of discounts via the CheapShark API.
 * 📊 Smart Deal Score: A proprietary algorithm that ranks deals not just by price, but by Community Popularity (active userbase), Critical Scores (Metacritic/Steam), and Discount Depth.
 * 🔍 Advanced Live Search: Prominent, real-time search bar in the navigation with "LIVE" status indicator and instant result filtering.
 * ❤️ Your Loved Deals: Save games to your local stash (persists on refresh) with a built-in Budget Planner to track your spending.
 * 🧠 Smart Meta-Data: Automatically generates concise game descriptions (e.g., "Top Rated • Released 2023") and displays clear Steam/Metacritic rating labels.
 * ⚡ Zero-Config Deployment: The entire app lives in one index.html file.
 * 🎨 Professional UI: Glassmorphism effects, 3D box art transformations, and a fully responsive layout.
 * 🌓 Theme System: Built-in Dark and Light mode toggle with persistence.
 * ⚡ Smart Deduplication: Automatically filters out duplicate listings to show only the lowest price for a specific game.
 * 📱 Mobile First: Fully optimized for touch devices with a collapsible sidebar and adaptive grid.
 * 💸 Maximized Monetization: Strategic, pre-integrated ad slots ready for AdSense (Leaderboard, Sidebar, In-Feed, Wishlist).

# 🚀 Quick Start
Option 1: Direct Download
 * Download the index.html file from this repository.
 * Double-click index.html to open it in Chrome, Firefox, Safari, or Edge.
 * That's it! The app is running.

Option 2: Local Server (Optional)
 * If you prefer running it via a local server (to avoid CORS issues with some strict browser extensions):
   * using python
     * python3 -m http.server 8000
     * then visit http://localhost:8000

# 🛠️ Technologies Used
This project demonstrates the power of modern frontend development without the complexity of build tools (Webpack/Vite).
 * Core: React 18 (via CDN)
 * Styling: Tailwind CSS (via CDN)
 * Compiler: Babel Standalone (via CDN)
 * Icons: FontAwesome 6
 * Data Source: CheapShark API
 * Fonts: Inter & Space Grotesk (Google Fonts)

# ⚙️ Configuration
Monetization

The app includes placeholder components for advertisements (<AdUnit />). To monetize:
 * Open index.html.
 * Search for the AdUnit component definition.
 * Replace the placeholder SVG/Text with your actual Google AdSense or ad network script code.

SEO

The file includes full SEO optimizations:
 * Open Graph (Facebook/LinkedIn) tags.
 * Twitter Card tags.
 * JSON-LD Structured Data for SoftwareApplication.
 * Semantic HTML5 structure.

# 🤝 Contributing
Contributions are welcome! Since this is a single-file project:
 * Fork the repository.
 * Make your changes directly in index.html.
 * Submit a Pull Request.

Note: Please ensure you do not break the single-file structure. All CSS and JS must remain embedded or loaded via CDN.

# 📄 License
This project is open source and available under the MIT License.

# 🙏 Acknowledgements
 * CheapShark API for providing the excellent, free game data.
 * Unsplash for placeholder assets.
 * Tailwind Labs for the utility-first CSS framework.
