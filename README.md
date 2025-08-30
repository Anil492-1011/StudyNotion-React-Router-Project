
# StudyNotion - React Router Project Starter

This project is a modern React single-page application (SPA) starter, featuring authentication pages, dashboard, and routing, styled with Tailwind CSS.

## Features
- ⚡ Fast, responsive SPA using React 18
- 🔗 Client-side routing with React Router DOM
- 🎨 Styled with Tailwind CSS and custom color palette
- 🔒 Authentication pages: Login, Signup, Dashboard
- 🏠 Home, About, and Contact navigation
- 🖼️ Asset management for images and SVGs

## Tech Stack
- React 18
- React Router DOM
- Tailwind CSS
- React Icons
- React Hot Toast

## Getting Started
1. **Install dependencies:**
	```bash
	npm install
	```
2. **Start the development server:**
	```bash
	npm start
	```
3. **Build for production:**
	```bash
	npm run build
	```

## Folder Structure

```
src/
  pages/         # Page components (Home, Login, Signup, Dashboard)
  components/    # Shared UI components (Navbar, Template, LoginForm, SignupForm)
  assets/        # Images and SVGs
  App.js         # Main app component
  App.css        # Tailwind and global styles
  index.js       # Entry point
public/
  index.html     # HTML template
  ...            # Static assets
tailwind.config.js  # Tailwind configuration
postcss.config.js   # PostCSS configuration
```

## Customization
- Update color palette and fonts in `tailwind.config.js`.
- Add new pages in `src/pages/` and update routing.
- Place new images in `src/assets/`.

---
This project is a great starting point for building scalable, modern React apps with authentication and custom design.
