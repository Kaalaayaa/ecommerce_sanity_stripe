# 🛍️ E-Commerce Platform

A full-stack e-commerce web application built with Next.js, Sanity CMS and Stripe. Live at [ecommerce-sanity-stripe-bice-pi.vercel.app](https://ecommerce-sanity-stripe-bice-pi.vercel.app)

---

## What it is

A fully functional online shop with a content-managed product catalogue, shopping cart, and real payment processing via Stripe.

---

## Features

- Product catalogue managed via Sanity CMS
- Shopping cart with quantity management
- Checkout flow with Stripe payment integration
- Order confirmation
- Fully responsive design
- Deployed on Vercel

---

## Tech Stack

- **Frontend:** Next.js, React
- **CMS:** Sanity
- **Payments:** Stripe
- **Deployment:** Vercel

---

## Installation & Usage

```bash
git clone https://github.com/Kaalaayaa/ecommerce_sanity_stripe.git
cd ecommerce_sanity_stripe
npm install
npm run dev
```

Add your environment variables in `.env.local`:

```
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_key
STRIPE_SECRET_KEY=your_key
NEXT_PUBLIC_SANITY_PROJECT_ID=your_id
```

---

## Live Demo

[ecommerce-sanity-stripe-bice-pi.vercel.app](https://ecommerce-sanity-stripe-bice-pi.vercel.app)
