# Swapforless Blog Frontend

This repository contains the Next.js frontend for the Swapforless Blog Modernization project.

## Purpose
- Serve the public-facing blog at blog.swapforless.com.
- Fetch and display content from Sanity.io.
- Provide a fast, SEO-optimized, and brand-aligned user experience.

## Getting Started

### 1. Prerequisites
- Node.js (v18+ recommended)

### 2. Setup
```bash
git clone https://github.com/OdayBakkour1/swapforless-blog.git
cd swapforless-blog
npm install
```

### 3. Development
```bash
npm run dev
```
App will be available at http://localhost:3000

### 4. Connecting to Sanity
- Set up environment variables for Sanity project ID, dataset, and read token (if needed).
- Use the official `@sanity/client` or `next-sanity` for data fetching.

### 5. Styling
- Tailwind CSS for utility-first styling.
- shadcn/ui for accessible, reusable UI components.

### 6. Deployment (Vercel)
- Deploy the app to Vercel for production and preview environments.
- Configure environment variables in Vercel dashboard.

### 7. Best Practices
- Use feature branches and pull requests for changes.
- Keep dependencies up to date.
- Ensure all pages include Navbar and Footer.
- Place reusable UI components in `/components/ui`.

---

For more, see the [Swapforless Blog Modernization Plan](../Swapforless_Blog_Modernization_Plan.md). 