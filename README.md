# 📬 Message Backend API

A modern backend API built with **Next.js 14**, **MongoDB**, **NextAuth**, **Zod**, and **Tailwind** — designed for secure, scalable message handling with authentication, validation, and real-time capabilities.

---

## 🚀 Tech Stack

| Layer      | Stack / Library                                                                    |
| ---------- | ---------------------------------------------------------------------------------- |
| Framework  | [Next.js](https://nextjs.org/) 🔥                                                  |
| Database   | [MongoDB + Mongoose](https://mongoosejs.com/) 🍃                                   |
| Auth       | [NextAuth.js](https://next-auth.js.org/) 🔐                                        |
| Validation | [Zod](https://zod.dev/) ✅                                                         |
| UI System  | [TailwindCSS](https://tailwindcss.com/) 🎨 + [Radix UI](https://www.radix-ui.com/) |
| Forms      | [React Hook Form](https://react-hook-form.com/) 📝                                 |
| Utils      | `dayjs`, `clsx`, `axios`, `bcryptjs`, `lucide-react`                               |
| Email      | `resend`, `react-email`, `@react-email/components` ✉️                              |
| AI         | [OpenAI SDK](https://www.npmjs.com/package/openai) 🤖                              |
| Carousel   | `embla-carousel` 🎠                                                                |

---

## 📂 Project Structure

```

/app              - Route handlers and API logic (Next.js App Router)
/lib              - Utility modules (auth, db, email, AI)
/schemas          - Zod validation schemas
/components       - UI and functional components
/hooks            - Custom React hooks
/styles           - Tailwind configuration

```

---

## 🛠️ Scripts

| Command         | Description                |
| --------------- | -------------------------- |
| `npm run dev`   | Start local development 🛠️ |
| `npm run build` | Build production bundle 📦 |
| `npm run start` | Start production server 🚀 |
| `npm run lint`  | Run ESLint checks 🧹       |

---

## 🔐 Features

- ✅ JWT + OAuth authentication via **NextAuth**
- ✅ Email support via **Resend**
- ✅ Form validation with **Zod**
- ✅ Modular code with strong typing (TypeScript)
- ✅ AI integrations using OpenAI SDK
- ✅ Tailwind-based responsive UI components

---

## ⚙️ Environment Variables

Create a `.env.local` file with the following keys:

```env
DATABASE_URL=<your-mongodb-uri>
NEXTAUTH_SECRET=<your-secret>
NEXTAUTH_URL=http://localhost:3000
OPENAI_API_KEY=<your-openai-key>
RESEND_API_KEY=<your-resend-key>
```

---

## 📦 Dependencies

> Full dependency list in `package.json`

Key packages:

- `next`, `react`, `mongoose`, `next-auth`
- `zod`, `axios`, `bcryptjs`, `react-hook-form`
- `tailwindcss`, `radix-ui`, `lucide-react`
- `openai`, `resend`, `react-email`

---

## 📝 License

MIT — free to use, modify, and distribute.
