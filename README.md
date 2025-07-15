# 🛒 Shopora – Cloud-Based E-Commerce App with Payment Gateway

Shopora is a modern, cloud-native e-commerce application designed for small to medium-sized businesses. It features a responsive storefront, secure authentication, admin dashboard, and integrated payment via Midtrans. Built with scalability and developer experience in mind using a monorepo architecture.

---

## 🚀 Features

### 🛍️ Customer-Facing
- Product listing with categories & filters
- Product detail page
- Shopping cart with real-time updates
- Checkout with shipping form
- Midtrans Snap payment gateway
- Order confirmation & payment status

### 🔐 Authentication
- NextAuth.js with social/email login
- Role-based access: `admin`, `user`

### 🧑‍💼 Admin Panel
- Dashboard with order overview
- Product CRUD (with image upload)
- Order management & status updates

---

## 🧰 Tech Stack

| Layer | Stack |
|-------|-------|
| Frontend | [Next.js](https://nextjs.org), [Tailwind CSS](https://tailwindcss.com), [TypeScript](https://www.typescriptlang.org), [React Query](https://tanstack.com/query) |
| Backend | [Node.js](https://nodejs.org), [Express.js](https://expressjs.com), [tRPC (optional)](https://trpc.io) |
| Database | [Supabase (PostgreSQL)](https://supabase.com) |
| Auth | [NextAuth.js](https://next-auth.js.org) |
| Payment | [Midtrans Snap](https://docs.midtrans.com) |
| DevOps | Vercel (FE), Railway/Supabase (API & DB), GitHub Actions (CI/CD), Docker |
| Media | Supabase Storage / Cloudinary |

---

## 📁 Monorepo Structure
