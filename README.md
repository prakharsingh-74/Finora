# 💼 Finora — Full Stack AI Finance Platform
---

## 🌟 About Finora

**Finora** is a next-generation AI-driven finance platform designed to help users analyze, automate, and manage financial operations efficiently.  
It combines intelligent data analysis, seamless UI, and secure backend integrations — all powered by modern full-stack technologies.

---


## Features
✅ AI-powered financial insights using Gemini API.
✅ Secure user authentication with Clerk.
✅ Real-time database and analytics with Supabase.
✅ Automated background tasks with Inngest.
✅ Transactional emails using Resend.
✅ Rate-limiting and security with ArcJet.
✅ Beautiful, accessible UI with Shadcn + Tailwind CSS.
✅ Fully typed backend with Prisma ORM.

## 🚀 Tech Stack

| Layer |
|-------|
| **Next js 15**
| **Supabase**
| **Prisma ORM**
| **Tailwind css + Shadcn UI**
| **Google gemini API** 
| **Clerk Auth** 
| **Email Service - Resend** 
| **Background Jobs - Inngest** 
| **Arcjet** 

---

## ⚙️ Environment Setup

Create a `.env` file in the root of your project and add the following environment variables:

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

## Installation
# 1. Clone the repository
git clone https://github.com/<your-username>/finora.git

# 2. Move into the project directory
cd finora

# 3. Install dependencies
npm install

# 4. Generate Prisma Client
npx prisma generate

# 5. Apply migrations to Supabase
npx prisma migrate deploy

#6. Running this project
npm run dev


## Folder Structure

finora/
├── prisma/
│   ├── schema.prisma        # Prisma schema models
│   └── migrations/          # Database migrations
├── src/
│   ├── app/                 # Next.js app directory
│   ├── components/          # UI components
│   ├── lib/                 # Utility functions and configurations
│   ├── pages/               # Routes and views
│   └── styles/              # Global and Tailwind styles
├── public/                  # Static assets
├── .env                     # Environment variables
├── package.json
└── README.md

