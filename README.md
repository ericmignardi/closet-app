# closet-app 🧥

A modern, full-stack application to manage your digital wardrobe. Organize, categorize, and track your clothing items with a sleek, responsive interface.

---

## Features

- **Wardrobe Management**: Effortlessly add, edit, and delete clothing items from your collection.
- **Categorization**: Organize your wardrobe by categories, colors, seasons, and custom tags.
- **Secure Authentication**: Robust user registration and login system powered by JWT and bcrypt.
- **Cloud Media Integration**: Seamlessly upload and manage clothing images using Cloudinary.
- **Responsive Design**: A premium, mobile-first UI that provides a consistent experience across all devices.

## Tech Stack

- **React 18**: Frontend library for building a dynamic and interactive user interface.
- **Zustand**: Lightweight and scalable global state management for React.
- **Node.js & Express**: High-performance backend REST API.
- **PostgreSQL & Sequelize**: Relational database storage with a powerful ORM for data modeling.
- **Tailwind CSS**: Utility-first CSS framework for modern, responsive styling.
- **Cloudinary**: Cloud-based media management for hosting clothing images.

---

## Installation & Setup

**Prerequisites:**

- Node.js (v18+)
- PostgreSQL (Local or NeonDB)
- Cloudinary Account (for image uploads)

```bash
# Clone the repository
git clone https://github.com/yourusername/closet-app.git
cd closet-app

# Install project dependencies
npm run build
```

**Environment Configuration:**

Create a `.env` file in the root directory with the following variables:

```env
DATABASE_URL=your_postgresql_url
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

## Usage

_Note: You need to start both the backend and frontend._

**Start the Backend:**

```bash
npm run dev
```

**Start the Frontend:**

```bash
cd frontend
npm run dev
```

---

## Things Learned

Developing `closet-app` provided deep insights into modern full-stack architecture and cloud integrations:

- **PERN Stack Synergy**: Mastering the integration of PostgreSQL, Express, React, and Node for production-grade apps.
- **Simplified State Management**: Leveraging Zustand as a clean, boilerplate-free alternative to Redux.
- **Relational Data Modeling**: Designing efficient schemas and associations using Sequelize ORM.
- **Cloud Media Pipelines**: Implementing secure client-side uploads and server-side management with Cloudinary.
- **UX-First Styling**: Using Tailwind CSS to build premium, accessible, and responsive layouts from scratch.
