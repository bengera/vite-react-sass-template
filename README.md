# Vite + React + Sass Template

A lightweight, fast-starting template using **React**, **Sass**, and **Vite** — perfect for frontend projects with modular SCSS and component-based design.

---

## 🚀 Quick Start

1. **Create a new project using this template:**
   - Click the green **"Use this template"** button on the repo page
   - Name your new repo
   - Clone it:


   ```bash
   git clone https://github.com/your-username/your-new-project
   cd your-new-project
   npm install
   npm run dev

Folder Structure

src/
│
├── App.jsx            # Main App component
├── main.jsx           # React DOM entry point
├── sass/
│   ├── abstracts/     # Variables, mixins
│   ├── base/          # Resets, typography
│   ├── components/    # Button, card styles etc.
│   ├── layout/        # Grid, container helpers
│   ├── utilities/     # Utility classes
│   ├── vendor/        # External SCSS (if any)
│   └── main.scss      # Single Sass entry point
└── index.html

Work with the latest packages

# Optionally remove old lock file and dependencies
rm -rf node_modules package-lock.json

# Reinstall everything fresh
npm install

# Update packages to latest non-breaking versions
npm update

Updating this template

# In the template repo folder
npm update        # Update all packages
npm install       # Reinstall updated versions
npm run dev       # Confirm everything still works
git add .
git commit -m "Update dependencies"
git push

Scripts
npm run dev       # Start local development server
npm run build     # Production build in /dist
npm run preview   # Preview built app

Using degit

npx degit your-username/vite-react-sass-template my-new-project
cd my-new-project
npm install
npm run dev

