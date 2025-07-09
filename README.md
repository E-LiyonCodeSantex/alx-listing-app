# ALX Listing App

The **ALX Listing App** is a modern Airbnb-style property listing page built using **Next.js**, **TypeScript**, **TailwindCSS**, and **ESLint**. This project is part of the ALX Front-End Pro Developer curriculum and serves as the foundational scaffold for a scalable, maintainable, and responsive web application.

---

## 🚀 Project Goals

- Scaffold a production-ready Next.js application
- Establish a clean and scalable folder structure
- Integrate TypeScript for type safety and maintainability
- Use TailwindCSS for responsive and accessible UI design
- Create reusable components for modular development
- Organize assets and constants for easy access and reuse

---

## 🧱 Project Structure

alx-listing-app/ ├── components/ # Reusable UI components │ └── common/ # Shared components like Card and Button ├── interfaces/ # TypeScript interfaces for props and data types ├── constants/ # Reusable constants (e.g., API URLs, config) ├── public/ │ └── assets/ # Images, SVGs, and other static assets ├── pages/ # Next.js pages (uses Pages Router) ├── styles/ # Global styles (TailwindCSS) ├── tailwind.config.js # TailwindCSS configuration ├── tsconfig.json # TypeScript configuration ├── .eslintrc.json # ESLint configuration └── README.md # Project documentation

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/alx-listing-app.git
cd alx-listing-app

### 2. Install Dependencies 
    ```bash
    npm install

### 3.Run the Development Server
    bash
    npm run dev
Then open your browser and go to: http://localhost:3000 you should see the default Next.js landing page or your custom homepage.

## 📁 Key Directories
components/: Contains reusable UI components like Card and Button.

interfaces/: Stores TypeScript interfaces for props and data models.

constants/: Holds configuration values and reusable constants.

public/assets/: Contains static images and SVGs used across the app.

##📌 Notes
This project uses the Pages Router, not the App Router.

TailwindCSS is configured via tailwind.config.js and styles/globals.css.

ESLint is set up to enforce clean and consistent code.

##🧪 Verification
To verify your setup:

Run npm run dev

Visit http://localhost:3000

Confirm that the app loads without errors

##📚 License
This project is part of the ALX Software Engineering Program. All rights reserved © 2025.

pages/index.tsx
