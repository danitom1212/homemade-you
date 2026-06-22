# 🛒 Homemade You — E-Commerce Dropshipping Platform

> A full-stack, production-ready dropshipping store built with modern web technologies.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-homemade--you.vercel.app-brightgreen?style=for-the-badge)](https://homemade-you.vercel.app)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 🚀 Features

- **Full product catalog** with categories: Pets, Home Decor, Kitchen, Custom Apparel
- **Printful API integration** — print-on-demand with automated order fulfillment
- **Supabase backend** — PostgreSQL database, authentication, real-time updates
- **Vercel deployment** — CI/CD pipeline, edge network, instant deploys
- **Responsive design** — mobile-first, optimized for all screen sizes
- **Admin-ready structure** — product management, image handling, category navigation

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 14, React, Tailwind CSS |
| Backend | Supabase (PostgreSQL + Auth + Storage) |
| Fulfillment | Printful API |
| Deployment | Vercel |
| Version Control | Git / GitHub |

---

## 📁 Project Structure

```
homemade-you/
├── app/                  # Next.js App Router pages
│   ├── (shop)/           # Product browsing & cart
│   ├── admin/            # Product management
│   └── api/              # API routes & webhooks
├── components/           # Reusable UI components
├── lib/                  # Supabase client, utilities
├── public/               # Static assets
└── types/                # TypeScript type definitions
```

---

## ⚙️ Getting Started

```bash
# Clone the repository
git clone https://github.com/danitom1212/homemade-you.git
cd homemade-you

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Add your Supabase and Printful credentials

# Run development server
npm run dev
```

---

## 🔑 Environment Variables

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key
PRINTFUL_API_KEY=your_printful_key
```

---

## 👤 Author

**Daniel Tomanian** — Full Stack Developer
- GitHub: [@danitom1212](https://github.com/danitom1212)
- Email: Danitom1212@gmail.com
