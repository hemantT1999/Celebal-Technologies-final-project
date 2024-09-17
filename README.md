# E-commerce Website

This is a fully functional e-commerce website built using **Next.js**, **Sanity**, and **Stripe**. The website includes product listings, filtering, a shopping cart system, and payment integration.

## Features

- **Product Listings**: Display a list of products with detailed information.
- **Search and Filtering**: Filter products based on categories, price, and more.
- **Shopping Cart**: Add/remove products from the cart and adjust quantities.
- **Checkout and Payment**: Integrated with Stripe for handling payments.
- **User-Friendly**: A smooth and responsive UI for seamless shopping experience.
- **Dynamic Product Management**: Manage product information dynamically via Sanity CMS.
- **Toast Notifications**: Interactive toast alerts for actions like adding items to cart.

## Tech Stack

- **Next.js**: Framework for server-side rendered React apps.
- **Sanity**: CMS for managing product data.
- **Stripe**: Payment gateway for handling secure transactions.
- **React Icons**: For adding scalable vector icons to the UI.
- **React Hot Toast**: For showing toast notifications.
- **Canvas Confetti**: To show celebration confetti on successful actions.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hemantT1999/E-commerce-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ecommerce
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
   
Open http://localhost:3000 to view the app in the browser.

# Environment Variables
## To run this project, you will need to add the following environment variables:

  - **SANITY_PROJECT_ID:** Your Sanity project ID.
  - **SANITY_DATASET:** The dataset name from Sanity.
  - **STRIPE_PUBLIC_KEY:** Your Stripe publishable API key.
  - **STRIPE_SECRET_KEY:** Your Stripe secret API key.

Create a .env.local file in the root directory with these values.
