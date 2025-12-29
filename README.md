# 👋 Hi, I’m Alfred

I’m a student full-stack developer who enjoys building real, end-to-end products — not just demos.

I’m especially interested in:
- turning ideas into working software
- clean UI with good UX
- authentication and backend logic
- shipping projects and learning from production bugs

I work best when I can **build, debug, and iterate** on a product until it actually runs in the real world.

<details>
<summary>My story</summary>


## 🧠 What I Can Do

- Build full-stack web apps from scratch
- Design and implement REST APIs
- Work with authentication (JWT, sessions)
- Integrate databases and external services
- Handle real deployment (frontend + backend)
- Debug production issues (CORS, env vars, auth, builds)
- Write clean, maintainable TypeScript and Python

**Tech I’ve worked with:**
- Next.js (App Router)
- TypeScript
- React
- Tailwind CSS / shadcn/ui
- FastAPI
- Supabase (Auth + Database)
- GSAP (animations)
- dnd-kit (accessible drag & drop)
- Vercel & Railway

---

# 🌱 NewJourney

**NewJourney** is a full-stack self-improvement web app that helps users manage tasks, subtasks, and personal growth in one focused system.

This project was built as a **real MVP**, not a tutorial clone — from authentication to deployment.

🔗 **Live demo**
- Frontend: https://newjourney-v2-r5311v35r-invisible-guys-projects.vercel.app  
- Backend: Deployed on Railway (FastAPI)

---

## ✨ Features

- 🔐 User authentication with Supabase
- ✅ Task management
  - Subtasks
  - Completion states
  - Drag-and-drop reordering
- ♿ Accessible drag-and-drop
  - Keyboard support
  - Screen-reader-friendly patterns
- 🎨 Modern UI
  - Tailwind CSS
  - shadcn/ui
  - GSAP animations
- 🌗 Light / dark mode
- 🚀 Fully deployed frontend and backend

---

## 🏗️ Architecture & Tech Stack

### Frontend
- Next.js (App Router)
- TypeScript
- Tailwind CSS
- shadcn/ui
- GSAP
- dnd-kit
- Zod

### Backend
- FastAPI
- Python
- Pydantic
- JWT verification (Supabase)

### Infrastructure
- Supabase (Auth + Database)
- Vercel (Frontend)
- Railway (Backend)

---

## 🔐 Authentication Flow

1. User logs in via Supabase Auth
2. Frontend retrieves an access token
3. API requests include: Authorization: Bearer <token>
4. FastAPI backend validates the token before serving protected routes

This keeps the frontend and backend cleanly separated while remaining secure.

---

## 🧪 What I Learned

- How real deployments break (and how to fix them)
- Handling CORS and preflight requests correctly
- Managing environment variables across platforms
- Building accessible drag-and-drop UI
- Knowing when a project is **done enough** to ship

A full day was spent debugging backend deployment and CORS issues — frustrating, but extremely valuable.

---

## 📈 Future Ideas

- Habits & routines
- Journaling / reflection
- Progress analytics
- Premium plans
- Mobile-first improvements

These are intentionally **not implemented yet** to keep the MVP focused.

---

## 📄 Notes

This project is part of my learning journey and portfolio.
It reflects how I approach building software: **ship first, refine later**.

</details>
