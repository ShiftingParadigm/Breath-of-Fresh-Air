# 🌐 Social Media Dashboard

A sleek and responsive social media dashboard with theme toggle functionality (Light / Dark / System) — built using Sass, HTML, and Gulp for task automation.

## 🚀 Features

- 📱 Responsive layout
- 🌗 Theme toggle with radio buttons (Light, Dark, System)
- ⚡ Built with Sass and compiled via Gulp
- 🎯 CSS utility functions (`rem()`, breakpoints)
- 🧠 Smart use of CSS grid and variables

## 📁 Project Structure

.
├── app
│ ├── scss
│ │ ├── components/
│ │ ├── utils/
│ │ ├── global/
│ │ └── style.scss
│ └── index.html
├── dist
│ └── css/
├── gulpfile.js
├── package.json
└── README.md

markdown
Copy
Edit

## 🔧 Tech Stack

- **HTML5**
- **Sass** (Modular architecture)
- **Gulp** (for compiling, autoprefixing, minification)
- **JavaScript** (optional toggle interactivity)

## 🛠 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https: //github.com/ShiftingParadigm/social-dashboard.git
   cd social-dashboard
Install dependencies

bash
Copy
Edit
npm install
Run Gulp

bash
Copy
Edit
gulp
Start developing

Gulp will watch .scss files, compile them, and reload your browser with Browsersync.

🎨 Customization
Edit variables in app/scss/utils/_variables.scss to change colors, font sizes, etc.

Adjust breakpoints in app/scss/utils/_breakpoints.scss for responsiveness.

Theme toggle logic is handled using radio inputs + CSS — no JS required!

🧪 To Do / Improvements
Add localStorage to remember selected theme

Add animations to toggle switch

Optimize for accessibility (ARIA attributes, focus states)

Add mobile drawer menu (optional)

Created with ❤️ by Sushant Rathore
