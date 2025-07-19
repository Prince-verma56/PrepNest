
# 🚀 **Full Stack AI Career Coach**

> **Your Personalized AI-Powered Career Guide**  
This project is a **Full Stack AI Career Coaching Platform** built to help users find career paths, upskill, and get AI-guided mentorship.  
It combines powerful AI APIs with seamless user onboarding, real-time interactions, and clean UI/UX.

---

## **🌟 Key Features**

- 🧠 **AI Career Guidance** (via Gemini API)  
- 🔐 **User Authentication & Onboarding**  
- 🎯 **Personalized Roadmaps**  
- ⏳ **Background Task Management**  
- ⚡ **Real-Time Recommendations**

---

## **🛠️ Tech Stack**

| Technology | Purpose |
|------------|---------|
| ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) | **Full-stack Framework (Frontend + Backend)** |
| ![Neon](https://img.shields.io/badge/Neon-1E90FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTIiIGhlaWdodD0iMTIiIHZpZXdCb3g9IjAgMCAxMiAxMiI+PHJlY3Qgd2lkdGg9IjEyIiBoZWlnaHQ9IjEyIiBmaWxsPSIjMUVBOEZGIi8+PC9zdmc+) | **Serverless Postgres Database** |
| ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) | **ORM for Database Access** |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) | **Responsive UI Styling** |
| ![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-111827?style=for-the-badge&logo=shadcn&logoColor=white) | **Beautiful & Accessible UI Components** |
| ![Inngest](https://img.shields.io/badge/Inngest-FF6B81?style=for-the-badge) | **Background Jobs & Event Workflows** |
| ![Clerk](https://img.shields.io/badge/Clerk-3B82F6?style=for-the-badge&logo=clerk&logoColor=white) | **User Authentication & Management** |
| ![Gemini API](https://img.shields.io/badge/Gemini_AI-FF5722?style=for-the-badge) | **AI-Powered Career Suggestions** |

---

## **🧑‍💻 Setup Instructions**

### **1️⃣ Clone the Repo & Install Dependencies**

```bash
npm install





DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=


## **Run the Project**


npm run dev


# Project Strcuture

/app               -> Next.js App Directory  
/components        -> Reusable UI Components (Shadcn UI)  
/lib               -> API, Inngest, Prisma helpers  
/db                -> Prisma DB Schema  
/public            -> Assets  





⚡ Why This Project?

This platform is designed to simulate how real-world AI coaching products work—combining:

Modern UI/UX

Real AI API integration

Scalable Backend Workflow with Inngest

Database Interaction via Prisma + Neon

Perfect for those who want to learn production-ready full-stack development with AI integration.