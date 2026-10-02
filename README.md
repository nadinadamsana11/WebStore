# WebStore — Web Applications Directory

> Discover, organize, and launch useful web applications from one clean and modern dashboard.

WebStore is a responsive web application directory designed to help users quickly discover and access popular online tools and services from a single place.

It provides a simple interface for browsing web applications by category, searching for specific tools, sorting results, saving favorites, and launching applications directly.

---

## ✨ Product Overview

WebStore works as a centralized directory for web applications.

Instead of remembering or searching for individual website links, users can browse a curated collection of web apps and quickly access the services they need.

The interface is designed with a modern dashboard-style layout, responsive cards, smooth interactions, dark/light themes, and an easy-to-use search and filtering system.

---

## 🚀 Key Features

### 🔎 Smart Search

Quickly search for web applications using:

- Application name
- Description
- Category

The search results update dynamically as the user types.

---

### 🗂️ Category Browsing

Applications are organized into different categories:

- All Web Apps
- Favorites
- AI Tools
- Productivity
- Development
- Design
- Entertainment
- Education
- Social Media

Users can switch between categories without reloading the page.

---

### ❤️ Favorites / Bookmarks

Users can save their favorite web applications for quick access later.

Favorites are stored using browser `localStorage`, so saved applications remain available after refreshing the page.

The Favorites section also displays the current number of saved applications.

---

### ⭐ Application Ratings

Every application card displays a rating to help users quickly understand the application's listed rating.

The application details modal also displays the rating together with the number of user ratings.

---

### 🔃 Multiple Sorting Options

Applications can be sorted using:

- Most Popular
- Top Rated
- Name (A-Z)

Popularity is calculated from the stored review count, while the rating option sorts applications according to their rating value.

---

### 🌙 Dark & Light Mode

WebStore includes a built-in theme switcher.

Users can switch between:

- Dark Mode
- Light Mode

The selected theme is stored in `localStorage` and automatically restored when the application is opened again.

---

### 📋 Application Details

Each application includes a dedicated Details view.

The details modal displays:

- Application icon
- Application name
- Category
- Rating
- User rating count
- Description
- Website URL
- Favorite status
- Visit Website button
- Copy URL button

---

### 🔗 One-Click Launch

Users can launch an application directly from its card or from the application details window.

Websites are opened in a new browser tab for convenient access.

---

### 📋 Copy Website URL

The application details window includes a Copy button that allows users to copy the selected application's URL to their clipboard.

---

### 📱 Responsive Design

WebStore is designed to work across different screen sizes:

- 📱 Mobile
- 📲 Tablet
- 💻 Desktop

The application automatically adapts its layout according to the available screen width.

---

### 🎨 Modern UI

The interface uses:

- Modern card-based layout
- Gradient backgrounds
- Rounded components
- Glass-style header
- Responsive application grid
- Smooth hover effects
- Animated transitions
- Font Awesome icons
- Inter typography

The UI is designed to remain clean and easy to navigate while displaying a large number of applications.

---

## 🧰 Technology Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Application structure |
| React 18 | UI and component rendering |
| JavaScript / JSX | Application logic |
| Tailwind CSS | Responsive styling |
| Font Awesome | Icons |
| Google Fonts | Inter typography |
| LocalStorage | Favorites & theme persistence |
| Babel Standalone | JSX compilation |

React 18, Tailwind CSS, Font Awesome, and Babel are loaded through CDN resources. :chatgpt-content-reference{index="1"}

---

## 🏗️ Application Structure

```text
WebStore
│
├── Header
│   ├── WebStore Branding
│   ├── Search
│   ├── Favorites
│   └── Theme Toggle
│
├── Hero Section
│   ├── Product Introduction
│   └── Featured Web Hub Message
│
├── Categories
│   ├── All Web Apps
│   ├── Favorites
│   ├── AI Tools
│   ├── Productivity
│   ├── Development
│   ├── Design
│   ├── Entertainment
│   ├── Education
│   └── Social Media
│
├── Application Directory
│   ├── Application Cards
│   ├── Ratings
│   ├── Details
│   ├── Favorites
│   └── Launch
│
├── Application Details Modal
│   ├── Application Information
│   ├── URL
│   ├── Copy URL
│   ├── Add Favorite
│   └── Visit Website
│
└── Footer
