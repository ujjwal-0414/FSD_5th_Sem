# Lumina Bookstore 📚

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-5-purple?logo=vite)
![License](https://img.shields.io/badge/License-MIT-green)

A modern, responsive online bookstore application built with **React**, **Vite**, and **React Router**.

---

## 🌟 Key Features

- **Dynamic Book Discovery**: Live book catalog fetched from the OpenLibrary API with curated fallback data and infinite scrolling.
- **Instant Search & Autocomplete**: Real-time debounced title and author search with preview suggestions.
- **Category Filtering**: Filter books across Fiction, Non-Fiction, and Sci-Fi.
- **Interactive Book Details**: Modal previews with descriptions, cover art, and pricing in INR (₹).
- **Cart Management**: Add books, adjust quantities with stock limit safeguards (max 15), remove items, and clear cart.
- **Coupon System**: Discount codes including `ABES50` / `LUMINA50` (50% off), `SANTA25OFF` (25% off), `NEWYEAR20` (20% off), and `HAPPY20DEAL` (20% off).
- **Checkout Modal**: Complete checkout workflow with order summary and customer details.
- **User Profile**: Profile overview, order history with delivery statuses, and editable account settings.
- **Theme Switcher**: Seamless toggle between Light and Dark modes.
- **Toast Notifications**: Non-intrusive feedback toasts for cart updates, settings changes, and searches.

---

## 👥 The Team

- **Ujjwal Gupta** ([@l-v-v-l](https://github.com/l-v-v-l))
- **Ujjwal Upadhyay**

*College project at **ABES Engineering College***

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation

```bash
npm install
```

### Development Server

Start the local Vite development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Production Build

Create an optimized production build in the `dist` folder:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

---

## 📁 Project Structure

```text
bookstore/
├── .gitignore              # Git ignore configuration
├── index.html              # HTML entry point for Vite
├── package.json            # Project dependencies and scripts
├── vite.config.js          # Vite configuration
├── README.md               # Project documentation
├── src/
│   ├── main.jsx            # React root mount
│   ├── App.jsx             # Router and layout configuration
│   ├── styles.css          # Full styling and design system
│   ├── context/
│   │   └── AppContext.jsx  # Global cart, theme, notification, and coupon state
│   ├── services/
│   │   └── bookService.js  # OpenLibrary API client and fallbacks
│   ├── components/
│   │   ├── Header.jsx      # Navigation header with live cart count
│   │   ├── Footer.jsx      # Site footer
│   │   ├── BookCard.jsx    # Book catalog card with action controls
│   │   ├── BookModal.jsx   # Detailed book view modal
│   │   ├── SettingsModal.jsx # Theme and notification settings
│   │   ├── CheckoutModal.jsx # Order placement modal
│   │   └── Toast.jsx       # Custom toast notification container
│   └── pages/
│       ├── HomePage.jsx    # Hero, search, filters, and books grid
│       ├── AboutPage.jsx   # Values, story, quote, and updated team credits
│       ├── CartPage.jsx    # Cart list, coupons, and order summary
│       └── ProfilePage.jsx # Profile, order history, and account settings
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

