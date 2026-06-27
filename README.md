# Nice Gadgets

A modern e-commerce web application for browsing, searching, and purchasing the latest gadgets, including smartphones, tablets, and accessories. This project is built using React, TypeScript, Vite, and SCSS. It features a fully responsive layout, a shopping cart, a favorites system, and dark/light theme options.

## Live Preview

Check out the live version of the project here:  
👉 [Nice Gadgets Deployed App](https://nice-gadgets-by-serggun.netlify.app/)  
_(Note: If you have a different Netlify site URL, please update this link accordingly)_

## Design Reference

The user interface of this project was designed in Figma. You can access the design reference here:  
🎨 [Phone Catalog - Figma Design Reference](https://www.figma.com/design/BUusqCIMAWALqfBahnyIiH/Phone-catalog--V2--Original-Dark?node-id=0-1&p=f&t=7dxyBSP0Jv7ZuRJt-0)

## Technologies Used

- **Core**: [React 19](https://react.dev/), [TypeScript](https://www.typescriptlang.org/)
- **Build Tool**: [Vite 8](https://vite.dev/)
- **Styling**: [Sass (SCSS)](https://sass-lang.org/) with BEM methodology
- **State & Routing**: [React Router DOM v7](https://reactrouter.com/) & React Context API
- **Accessibility & Focus Management**: [Radix UI](https://www.radix-ui.com/), [Focus Trap React](https://github.com/focus-trap/focus-trap-react)
- **UI Elements & Carousels**: [Swiper](https://swiperjs.com/)
- **Linters & Formatters**: ESLint, Stylelint, Prettier, Husky, commitlint, and lint-staged

## Features

- **Product Categories**: Separate product catalogs for Phones, Tablets, and Accessories.
- **Detailed Product Pages**: Displays comprehensive technical specs, image gallery, related product suggestions, and variation selection (capacity, color).
- **Shopping Cart**: Real-time management of selected items (add/remove, adjust quantities), total price calculation, and mock checkout sequence, persisted with local storage.
- **Favorites Wishlist**: Users can flag items to save for later with badges reflecting the count.
- **Debounced Catalog Search**: Instantly filters products by name inside categories using a debounced search input.
- **Theme Customization**: Responsive theme toggle providing Dark, Light, and System Default mode preferences.
- **Responsive Layout**: Designed mobile-first, ensuring smooth usage across mobile, tablet, and desktop viewports, with a specialized burger navigation menu.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Make sure you have Node.js (version 18 or higher recommended) and npm installed.

### Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/SergGun/nice_gadgets.git
   cd nice_gadgets
   ```

2. **Install dependencies**:

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the project locally**:
   ```bash
   npm start
   # or
   yarn start
   ```
   This will start the development server and automatically open the application in your web browser.

### Other NPM Scripts

- **Build for production**:
  ```bash
  npm run build
  ```
- **Preview production build locally**:
  ```bash
  npm run preview
  ```
- **Run linter checks**:
  ```bash
  npm run lint
  ```
- **Auto-fix linter issues**:
  ```bash
  npm run lint:fix
  ```
- **Format code files**:
  ```bash
  npm run format
  ```
- **Type-check files**:
  ```bash
  npm run typecheck
  ```

## Git Workflow & Commits

- **Branches**: Direct push to the `main` branch is disabled. All modifications must be submitted via pull requests (PR) using feature or bugfix branches.
- **Commit Messages**: Follows the [Conventional Commits](https://www.conventionalcommits.org/) specification (enforced by Husky and commitlint on every commit).
