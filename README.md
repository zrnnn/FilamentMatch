FilamentMatch 🧵

FilamentMatch is an interactive, modern web tool designed to help 3D printing enthusiasts find the perfect filament for their specific needs. By weighing priorities like strength, stiffness, heat resistance, and price, the tool dynamically ranks materials from Bambu Lab and popular third-party brands.

✨ Features

🎯 Smart Priority Ranking: Drag and drop criteria (Strength, Price, Heat, etc.) to reorder them. The algorithm updates the ranking instantly based on your specific needs.

📊 Visual Radar Charts: Compare up to 3 filaments side-by-side with dynamic, color-coded net diagrams.

📚 Extensive Database: Includes data for 30+ filaments from:

Bambu Lab (Basic, Matte, CF, Tough, etc.)

Prusament

Polymaker

eSun

Overture

And more...

💰 Price/kg Calculator: Automatically normalizes prices to compare value per kilogram, regardless of spool size (e.g., 0.5kg vs 1kg spools).

🎨 Modern UI: Fully responsive Glassmorphism design with Dark/Light mode support.

🔍 Advanced Filtering: Filter by brand, material type, or "AMS Ready" status.

🚀 Quick Start

This is a single-file application built with Vue 3 (CDN) and Tailwind CSS (CDN). No build steps or npm install required!

Option 1: Run Locally

Download index.html.

Open it in any web browser (Chrome, Firefox, Safari).

Option 2: Host on GitHub Pages (Free)

Fork or clone this repository.

Go to Settings -> Pages.

Set Source to Deploy from a branch and select main (or master).

Your site will be live at https://<your-username>.github.io/FilamentMatch/.

🛠️ Technologies Used

Vue.js 3: Reactive UI and logic.

Tailwind CSS: Modern styling and dark mode.

Chart.js: Rendering the interactive radar comparison charts.

Google Fonts: Inter & JetBrains Mono typography.

📝 Data Sources

Technical data (Tensile Strength, Stiffness, Impact, HDT) is aggregated from official Technical Data Sheets (TDS) provided by manufacturers as of 2025/2026.

Note: This is an unofficial guide. Always refer to specific manufacturer instructions for printing.
