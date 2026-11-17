# Kshaum / Ship of Desert

A luxury sustainable fashion e-commerce web application built with [Next.js](https://nextjs.org), React 19, Tailwind CSS, and MongoDB.

## Features

- **Curated Collections**: Browsing and filtering for signature pieces (Dresses, Sets, Skirts, Trousers).
- **Interactive Experience**: Smooth transitions and animations powered by Framer Motion.
- **Admin Dashboard**: Comprehensive product catalog, order tracking, and registered user management.
- **Secure Authentication**: Session and role-based access control with NextAuth.
- **Robust Database**: MongoDB Atlas integration with Mongoose caching and route performance tracking.

## Getting Started

### Prerequisites

- Node.js (v18.x or v20.x+)
- npm, pnpm, or yarn
- MongoDB connection string

### 1. Environment Setup

Create a `.env` file in the root directory with the necessary credentials (do not commit this file):

```env
MONGODB_URI=your_mongodb_connection_string
AUTH_SECRET=your_auth_secret
NEXTAUTH_SECRET=your_auth_secret
AUTH_TRUST_HOST=true
NEXTAUTH_URL=http://localhost:3000

NEXT_PUBLIC_RECAPTCHA_SITE_KEY=your_recaptcha_site_key
RECAPTCHA_SECRET_KEY=your_recaptcha_secret_key
RECAPTCHA_MIN_SCORE=0.5
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Frontend**: React 19, Tailwind CSS v4, Framer Motion
- **Database**: MongoDB Atlas with Mongoose
- **Authentication**: NextAuth.js
- **Deployment**: Vercel
