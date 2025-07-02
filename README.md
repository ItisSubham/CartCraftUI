# 🚀 CartCraftUI - Digital Marketplace
![Preview](./CartCraftUI.png)

A modern, full-stack digital marketplace built with Next.js 14, featuring user authentication, payment processing, and file uploads. Sell and buy digital products with ease!

## ✨ Features

### Core Functionality
- 🛍️ **Digital Marketplace** - Buy and sell digital products
- 🔐 **Authentication** - Secure user authentication with Kinde
- 🔑 **OAuth Integration** - Google and GitHub login support
- 💰 **Payment Processing** - Stripe integration for secure payments
- 🏪 **Marketplace Functionality** - Stripe Connect for seller payouts
- 📁 **File Upload** - UploadThing integration for product files and images

### Technical Features
- 🌐 **Next.js App Router** - Modern routing with App Directory
- 🪝 **Stripe Webhooks** - Real-time payment processing
- 💿 **Supabase Database** - PostgreSQL database hosting
- 💨 **Prisma ORM** - Type-safe database queries
- ✅ **Server Validation** - Zod schema validation
- 🎨 **Modern UI** - Tailwind CSS + shadcn/ui components
- 📧 **Email System** - Resend integration with React Email
- 🚀 **Deployment Ready** - Optimized for Vercel deployment
- ⚡ **React Streaming** - Optimized loading states
- 📊 **Stripe Dashboard** - Express dashboard integration

## 🛠️ Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Database:** Supabase (PostgreSQL)
- **ORM:** Prisma
- **Authentication:** Kinde
- **Payments:** Stripe + Stripe Connect
- **File Uploads:** UploadThing
- **Styling:** Tailwind CSS + shadcn/ui
- **Email:** Resend + React Email
- **Deployment:** Vercel


## 📁 Project Structure

```
├── app/
│   ├── (dashboard)/          # Protected dashboard routes
│   ├── api/                  # API routes
│   │   ├── auth/            # Authentication endpoints
│   │   ├── stripe/          # Stripe webhooks
│   │   └── uploadthing/     # File upload endpoints
│   ├── components/          # React components
│   │   ├── form/           # Form components
│   │   └── ui/             # UI components
│   ├── lib/                # Utility functions
│   └── actions.ts          # Server actions
├── components/             # shadcn/ui components
├── lib/                   # Shared utilities
├── prisma/               # Database schema
└── public/              # Static assets
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

Made with 💙 by [Subham](https://github.com/ItisSubham)