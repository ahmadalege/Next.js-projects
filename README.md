# 🔐 Next.js Auth App

A simple authentication app built with **Next.js** and **Auth.js** (NextAuth), supporting:

- 🔑 Google Sign-In
- 🐱 GitHub Sign-In
- ✉️ Magic Link via Email

---

## 🚀 Demo

> Coming soon...

---

## 📦 Tech Stack

- [Next.js](https://nextjs.org/)
- [Auth.js (NextAuth)](https://authjs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [MongoDB (mongoose)](https://www.mongodb.com/)

---

## 🧑‍💻 Features

- ✅ Sign in with Google or GitHub
- ✅ Session management
- ✅ Easy route protection
- ✅ Server & client component support

---

## 🛠️ Installation

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/next-auth-app.git
cd next-auth-app

# 2. Install dependencies
npm install

# 3. Set up environment variable
touch .env

# 4. Run the dev server
npm run dev
```

## ⚙️ .env.local Configuration

Create a `.env.local` file in the root of your Next.js project with the following variables:

```env
# ========================
# MongoDB Connection
# ========================
MONGO_URI=mongodb://127.0.0.1:27017/authProject

# ========================
# NextAuth Secret Key
# ========================
AUTH_SECRET=your_nextauth_secret_key

# ========================
# GitHub OAuth Provider
# ========================
AUTH_GITHUB_ID=your_github_client_id
AUTH_GITHUB_SECRET=your_github_client_secret

# ========================
# Google OAuth Provider
# ========================
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

## 🧩 OAuth Setup

Create OAuth credentials at:

- [Google](https://console.cloud.google.com/apis/credentials/)
- [GitHub](https://github.com/settings/developers/)

Feel free to fork, improve, or give a ⭐ on GitHub!
