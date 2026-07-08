<div align="center">

  <h1>📸 Pulse Social</h1>
  <p><strong>A modern, high-performance social media web application inspired by Instagram.</strong></p>

  [![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
  [![Vite](https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

</div>

---

## 🌟 Overview

**Pulse Social** is a frontend social platform that delivers a smooth, native-feeling user experience. Built with **React** and styled using **Tailwind CSS**, Pulse Social translates the core features of photo-sharing networks into a clean, modern single-page application (SPA).

> 💡 **Note:** This project is currently configured with a mock data layer, making it instantly runnable out of the box with zero backend setup required!

---

## ✨ Features

### 📰 Feed & Interaction
* **Interactive Feed:** Infinite scroll-style feed supporting image posts, double-tap to like, post bookmarking, and expand-to-comment modals.
* **Stories Bar:** Active user story tray with animated unread rings and interactive full-screen story preview overlays.
* **Explore Page:** Responsive CSS Grid layout showcasing trending content and real-time client-side search filtering.

### 👤 Profile & Customization
* **Rich User Profiles:** View post grids, saved content, user bio info, dynamic follower counts, and editable settings.
* **Theme Engine:** Built-in Dark and Light themes powered by React Context API and CSS custom properties.

### 🎨 Creation & Media
* **Post Creator:** Dynamic image upload preview modal with caption inputs, filter previews, and location tagging layout.
* **Fully Responsive:** Mobile-first user interface with tailored navigation bars for mobile (bottom bar) and desktop (sidebar).

---

## 🛠️ Tech Stack

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Framework** | [React](https://react.dev/) | UI Component Library |
| **Build Tool** | [Vite](https://vitejs.dev/) | Lightning-fast development server & bundler |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) | Utility-first CSS framework |
| **Icons** | [Lucide React](https://lucide.dev/) | Clean, consistent SVG icon set |
| **Routing** | [React Router v6](https://reactrouter.com/) | Client-side routing |
| **State** | React Context API | Theme switching & global post/user state management |

---

## 📁 Folder Structure

```text
pulse-social/
├── 📁 public/            # Static assets & public icons
├── 📁 src/
│   ├── 📁 assets/        # Media assets (images, logos)
│   ├── 📁 components/    # Reusable UI elements (Navbar, Feed, StoryBar, PostCard)
│   ├── 📁 context/       # Auth, Theme, & Feed state providers
│   ├── 📁 data/          # Mock JSON datasets for feeds and profiles
│   ├── 📁 hooks/         # Custom React hooks (useTheme, useFeed)
│   ├── 📁 pages/         # Top-level views (Home, Profile, Explore, Settings)
│   ├── App.jsx           # Main router & app layout configuration
│   ├── index.css         # Tailwind directives & custom CSS
│   └── main.jsx          # App entry point
├── .gitignore
├── index.html
├── package.json
├── tailwind.config.js
└── README.md
