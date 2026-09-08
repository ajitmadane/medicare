# MediCare Pharmacy

A modern React + Vite pharmacy storefront designed to showcase healthcare products, categories, featured medicines, a shopping cart, and a demo checkout flow.

This project is a front-end demo that simulates a trusted medicine and wellness shopping experience for patients and customers.

## Overview

MediCare Pharmacy is a responsive ecommerce-style landing page for a pharmacy brand. It includes:

- Hero section with CTAs and pharmacy branding
- Product categories with icon-based navigation
- Featured medicines and full product catalog
- Search and category filtering
- Product detail modal
- Add-to-cart workflow with quantity updates
- Cart drawer and demo checkout modal
- Customer reviews, FAQs, and contact information
- Local storage persistence for cart state

## Tech Stack

- React 19
- TypeScript
- Vite 6
- Tailwind CSS
- Lucide React icons
- Motion animations

## Project Structure

```bash
medicare/
├── public/
├── src/
│   ├── components/
│   ├── data/
│   ├── assets/
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   ├── types.ts
│   └── vite-env.d.ts
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── metadata.json
└── README.md
```

## Features

### Product catalog
- Filter by category
- Product cards with ratings, pricing, and stock status
- Quick add-to-cart action
- Product modal with details, ingredients, dosage and manufacturer information

### Cart and checkout
- Cart drawer with item quantity controls
- Persistent cart state using localStorage
- Demo checkout modal for reservation flow
- Toast notifications for cart actions

### Customer experience
- Smooth scrolling navigation
- Active section highlighting in the header
- Contact, FAQ, and review sections
- Mobile-friendly, modern layout

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js 18+
- npm or yarn

### Install dependencies

```bash
npm install
```

### Run the app in development mode

```bash
npm run dev
```

The project runs on:

```bash
http://localhost:3000
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Type check

```bash
npm run lint
```

## Notes

- This is a frontend demo and not a real pharmacy backend or prescription fulfillment system.
- Product information is represented using static demo data.
- Prescription products are marked for informational purposes only.

## Scripts

```json
{
  "dev": "vite --port=3000 --host=0.0.0.0",
  "build": "vite build",
  "preview": "vite preview",
  "clean": "rm -rf dist server.js",
  "lint": "tsc --noEmit"
}
```

## License

This project is provided as a demo storefront for educational and presentation purposes.

## Author

MediCare Pharmacy Demo Storefront
