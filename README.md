# CareerSphere: Full Stack AI Career Coach

A modern AI-powered career coach platform built with **Next.js**, **NeonDB**, **Tailwind CSS**, **Prisma**, **Inngest**, **Shadcn UI**, and **Google Gemini AI**.  
Accelerate your career with AI-generated resumes, interview prep, industry insights, and more.

![CareerSphere](https://github.com/user-attachments/assets/eee79242-4056-4d19-b655-2873788979e1)

---

## ✨ Features

- **AI Resume Builder:** Create, edit, and improve resumes with AI suggestions.
- **Interview Prep:** Practice with AI-generated quizzes and get personalized improvement tips.
- **Industry Insights:** Explore trends and stats across 50+ industries.
- **24/7 AI Support:** Get instant help and feedback anytime.
- **Beautiful UI:** Responsive, accessible, and modern design with Shadcn UI and Tailwind.
- **Secure Auth:** User authentication via Clerk.
- **Markdown Editing:** Easy content customization with markdown support.

---

## 🚀 Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS, Shadcn UI
- **Backend:** Next.js API routes, Prisma ORM, NeonDB
- **AI:** Google Gemini API (Generative AI)
- **Auth:** Clerk
- **Background Jobs:** Inngest

---

## 🛠️ Getting Started

1. **Clone the repo:**
   ```sh
   git clone https://github.com/your-username/careersphere.git
   cd careersphere
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Configure environment variables:**  
   Create a `.env` file in the root with the following:
   ```
   DATABASE_URL=

   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

   GEMINI_API_KEY=
   ```

4. **Run the development server:**
   ```sh
   npm run dev
   ```

5. **Open [http://localhost:3000](http://localhost:3000) in your browser.**

---

## 📂 Project Structure

- `/app` – Next.js app directory (pages, layouts, components)
- `/actions` – Server actions for resume, interview, etc.
- `/components` – Shared React components (header, theme, etc.)
- `/data` – Static data (features, testimonials, FAQs)
- `/lib` – Utilities and helpers
- `/public` – Static assets (logo, images)
- `/prisma` – Prisma schema and migrations

---

## 🧑‍💻 Scripts

- `npm run dev` – Start development server
- `npm run build` – Build for production
- `npm run start` – Start production server
- `npx prisma migrate dev` – Run database migrations

---

## 📝 License

MIT
