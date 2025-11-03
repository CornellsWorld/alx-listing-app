🏠 ALX Listing App
Project Overview

ALX Listing App is a responsive web application inspired by Airbnb’s home listing platform.
The goal of this project is to replicate a modern, user-friendly property listing interface, allowing users to browse, filter, and explore vacation rentals with a clean, visually rich design.

The project demonstrates best practices in Next.js, TypeScript, and TailwindCSS, focusing on performance, scalability, and maintainable component-driven architecture.

🎯 Key Features

Fully responsive design (desktop, tablet, and mobile)

Property listing cards with images, pricing, and details

Filter and sorting options

Modern and minimalist UI inspired by Airbnb

Built with reusable components for scalability

🧱 Project Structure
alx-listing-app/
├── components/         # Reusable UI components (Navbar, ListingCard, FilterBar, Footer, etc.)
├── interfaces/         # TypeScript types and interfaces (e.g. Listing, User, FilterOptions)
├── constants/          # Constant data such as categories, dummy listings, or URLs
├── public/
│   └── assets/         # Static files (images, icons, logos, etc.)
├── pages/              # Application pages (using Next.js Pages Router)
│   ├── index.tsx       # Home / Listing page
│   ├── _app.tsx        # Root layout file
│   └── _document.tsx   # Custom document setup
├── styles/             # Global and Tailwind CSS styles
│   └── globals.css
├── tailwind.config.js  # Tailwind configuration
├── tsconfig.json       # TypeScript configuration
├── next.config.mjs     # Next.js configuration
└── README.md           # Documentation

📁 Directory Purpose

components/ – Reusable building blocks such as buttons, cards, navigation bars, and layout sections.

interfaces/ – TypeScript interfaces defining the shape of data objects like listings, filters, or users.

constants/ – Stores app-wide constants (filter options, property types, etc.).

public/assets/ – Contains static assets like images, logos, and icons.

⚙️ Tech Stack

Next.js (with Pages Router)

TypeScript (for type safety)

TailwindCSS (for styling and responsive layouts)

ESLint (for linting and clean code enforcement)

💻 Running the Project Locally

Follow these steps to set up the project on your Windows system:

1️⃣ Clone the repository
git clone <your-repo-url>
cd alx-listing-app

2️⃣ Install dependencies
npm install

3️⃣ Run the development server
npm run dev


Then open your browser and navigate to:
👉 http://localhost:3000

You should see the homepage matching your Figma design (listing page layout with image cards and filters).

🧩 Design Reference

The UI is based on the “Project Airbnb” Figma design, which showcases:

Hero section with background image and tagline

Grid-based property listings

Top navigation bar and search filters

Responsive views for tablet and mobile
