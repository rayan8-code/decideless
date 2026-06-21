# ⚡ DecideLess

> **Your mind, finally free. AI that cuts through indecision — so you can focus on living.**

**🌍 Live Demo:** [http://decide-less-wgz9.vercel.app/](http://decide-less-wgz9.vercel.app/)

DecideLess is an intelligent, mobile-first web application designed to eliminate decision fatigue. By learning your preferences, habits, and tastes, DecideLess acts as your personal AI decision-maker, giving you instant, personalized choices without the overthinking.

---

## ✨ Features

- **🧠 AI-Powered Decision Engine:** Integrates both Google's Gemini and OpenAI to provide contextual, hyper-personalized recommendations.
- **📱 Mobile-First PWA:** Built as a Progressive Web App (PWA) with a seamless, native-like mobile experience including bottom navigation and sleek UI transitions.
- **👤 Smart Onboarding & Profiles:** Learns who you are from day one. The more you use it, the better it understands your unique tastes.
- **💬 Conversational UI:** Chat interface to easily ask for recommendations, brainstorm ideas, or just let the AI pick for you.
- **📚 Personal Library & History:** Automatically saves your favorite choices and past decisions for easy access.
- **🔒 Secure Authentication:** Powered by Firebase Authentication for seamless user login and data protection.

## 🛠️ Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/) (App Router)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/) & [Framer Motion](https://www.framer.com/motion/) for fluid animations
- **State Management:** [Zustand](https://zustand-demo.pmnd.rs/)
- **Backend & Database:** [Firebase](https://firebase.google.com/) (Firestore, Auth, Admin SDK)
- **AI Integration:** Google Gemini API & OpenAI API
- **Email/Notifications:** [Resend](https://resend.com/) & [React Email](https://react.email/)
- **Task Scheduling:** [Upstash QStash](https://upstash.com/)
- **Icons:** [Lucide React](https://lucide.dev/)

## 📂 Architecture & Structure

- `/app`: Next.js App Router pages supporting core features like Home, Chat, Library, Onboarding, Profile, and Authentication.
- `/components`: Modular UI components and layout wrappers (e.g., Bottom Navigation, Toast notifications).
- `/store`: Centralized application state using Zustand.
- `/lib`: Utility functions and integrations (Firebase client/admin configuration, AI helpers).
- `/hooks`: Custom React hooks for reusable logic across components.

## 📄 License

This project is currently private and proprietary. All rights reserved.
