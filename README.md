# SmartFlow ERP - Java Backend Capstone Project

SmartFlow is a modular, scalable ERP platform designed to streamline core business functions like procurement, inventory, finance, HR, and supplier management. Built as part of the Qucoon TeSA Java Backend Capstone Project, this project showcases both frontend and backend readiness for enterprise applications.

## 🚀 Features Implemented (MVP)

- **Company Sign-in** with email domain validation
- **Role-based workspace routing** (e.g. Chevron, Qucoon)
- **Responsive Landing Page**
  - Hero section with background image
  - Features overview
  - Modular architecture highlight
  - About, Contact, and FAQs
- **Company Dashboard**
  - Sidebar with module links
  - Main panel with summary cards and quick actions
- **Dark Mode Toggle**
  - Theme persists across pages
- **Fully responsive layout** across devices

## 🏗 Tech Stack

- HTML5
- CSS3 (Custom styling with Flexbox/Grid)
- JavaScript (ES6+)
- LocalStorage (for login persistence and theme)

## 📁 Project Structure

- /images → Logos, icons, illustrations
- /css → Custom CSS stylesheets
- /index.html → Landing page
- /signin.html → Sign-in form with email validation
- /company-dashboard.html → Company-specific dashboard


## 🔐 Demo Companies

| Company | Email Domain | Logo |
|--------|------------------|------|
| Chevron | `@chevron.com` | ✅ |
| Qucoon  | `@qucoon.com`  | ✅ |

Login emails are validated against domain to route to appropriate dashboard.

## 🌙 Dark Mode Support

- Dark mode is default on load
- Toggle button provided in the nav drawer
- Theme choice is stored in `localStorage` and persists between pages

## 📄 License

<!-- This project is licensed under the [MIT License](LICENSE). -->

## ✨ Acknowledgements

- Qucoon TeSA Java Backend Specialization
- Font Awesome (icons)
- Google Fonts (Poppins, Roboto)
