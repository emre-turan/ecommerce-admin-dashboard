# Full Stack E-Commerce Admin Dashboard

Welcome to the repository for my Full Stack E-Commerce Admin Dashboard. This project is a comprehensive e-commerce solution with a fully functional admin dashboard, CMS, and API.

## Features

- **Admin Dashboard**: The project uses Next.js 13 App Router, React, and Tailwind to create a robust and user-friendly admin dashboard.

- **State Management**: Zustand is used for state management.

- **Dark Mode Support**: The dashboard supports dark mode for a comfortable user experience.

- **Media File Management**: Cloudinary is used for media file management.

- **UI**: The project uses Shadcn UI for a sleek and modern user interface.

- **Authentication**: Clerk for user authentication.

- **Order Creation**: The dashboard supports order creation and management.

- **Payments**: The project integrates Stripe for payments and also supports Stripe webhooks.

- **Database Management**: The project uses MySQL for database management, with Prisma as the ORM. I also use PlanetScale for database scaling.

- **Multi-Vendor Support**: Users can control multiple vendors/stores through this single CMS! For example, a user can have a "Shoe store", a "Laptop store", and a "Suit store", and the CMS will generate API routes for all of those individually!

## User Capabilities

Users can:

- Create, update, and delete categories.
- Create, update, and delete products.
- Upload multiple images for products and change them whenever they want.
- Create, update, and delete filters such as "Color" and "Size", and then match them in the "Product" creation form.
- Create, update, and delete "Billboards" which are these big texts on top of the store page. Users can attach them to a single category, or use them standalone. The Admin generates API for all of those cases!
- Search through all categories, products, sizes, colors, billboards with included pagination.
- Control which products are "featured" so they show on the homepage.
- See orders, sales, etc.
- See graphs of your revenue etc.

## Learning Experience

This project has been a significant learning journey, providing me with a wealth of software knowledge and experience. It's been a pleasure to see the project grow and evolve, and I'm excited to see where it goes next.

## Live Demo

You can view the live demo of the project [here](https://ecommerce-admin-dashboard-liard.vercel.app/).
