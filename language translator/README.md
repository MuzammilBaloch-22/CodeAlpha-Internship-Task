<div align="center">

  <img src="https://camo.githubusercontent.com/c8c943e01b13a6125acbfe1e129e313548ed819db3dc46d2b83376c604659843/68747470733a2f2f6c68332e676f6f676c6575736572636f6e74656e742e636f6d2f642f3150754e327364596b4755525246586c47645f7a416a585172597a6d50614f68693d773230303f61757468757365723d30" alt="CodeAlpha Logo" width="180"/>

  # 🌐 AI-Powered Language Translator
  
  <p align="center">
    <strong>A Modern, Cloud-Native Translation System leveraging Google Gemini AI</strong>
    <br />
    Developed as part of the <b>CodeAlpha Artificial Intelligence Internship</b>
  </p>

  <div>
    <img src="https://img.shields.io/badge/Internship-CodeAlpha-blue?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Model-Gemini%202.5%20Flash-orange?style=for-the-badge&logo=googlegemini" />
    <img src="https://img.shields.io/badge/Backend-Supabase%20Edge%20Functions-green?style=for-the-badge&logo=supabase" />
    <img src="https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge" />
  </div>

  <br />

  [**🚀 View Live Demo**](https://languagestranslat0r.netlify.app/)

</div>

---

## ✨ Project Overview

This **AI Language Translator** is a sophisticated, serverless application that provides near-instant translations. By combining the ultra-fast **Gemini 2.5 Flash** model with a robust **TypeScript-React** frontend, it ensures a premium user experience with high linguistic accuracy.

### 🔥 Key Highlights
* 🌍 **Global Support:** Seamlessly translate between dozens of languages.
* ⚡ **Serverless Power:** Uses **Supabase Edge Functions** (Deno) for a scalable, low-latency backend.
* 🧠 **LLM Driven:** Powered by Google's latest **Gemini 2.5 Flash** for nuanced translations.
* 🎨 **Modern UI:** Built with **shadcn/ui** and **Tailwind CSS** for a clean, accessible interface.
* 🔐 **Secure:** API keys are protected via server-side environment variables.

---

## 🛠️ Tech Stack

### **Frontend**
![React](https://img.shields.io/badge/React-18-blue?style=flat&logo=react) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8-blue?style=flat&logo=typescript) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-teal?style=flat&logo=tailwindcss) ![Vite](https://img.shields.io/badge/Vite-6.0-purple?style=flat&logo=vite)

### **Backend & Infrastructure**
![Supabase](https://img.shields.io/badge/Supabase-Edge_Functions-green?style=flat&logo=supabase) ![Deno](https://img.shields.io/badge/Deno-Backend-lightgrey?style=flat&logo=deno) ![Gemini AI](https://img.shields.io/badge/Gemini_2.5_Flash-AI-orange?style=flat&logo=google) ![Netlify](https://img.shields.io/badge/Netlify-Deployment-00C7B7?style=flat&logo=netlify)

---

## 🔄 How It Works (Workflow)



1.  **User Input:** The user enters text in the React frontend.
2.  **Edge Function:** The request is routed to a **Supabase Edge Function** to keep the API keys secure.
3.  **Gemini AI:** The backend communicates with the **Gemini 2.5 Flash API** to process the translation.
4.  **UI Update:** The translated text is returned and displayed instantly via **TanStack React Query**.

---

## 📂 Project Structure

```text
├── /src                    # Frontend Source (React + TypeScript)
│   ├── /components         # UI Components (shadcn/ui)
│   ├── /pages              # Main Application Pages
│   ├── /integrations       # Supabase Client Logic
│   └── /hooks              # Custom Logic & API Hooks
├── /supabase               # Backend Functions
│   └── /functions          # Deno-based Edge Functions (Gemini Integration)
└── /public                 # Static Assets
⚙️ Setup & Installation
Clone the Repo:

Bash

git clone [https://github.com/MuzammilBaloch-22/Language-Translator.git](https://github.com/MuzammilBaloch-22/Language-Translator.git)
Environment Setup: Add your variables to .env (Frontend) and Supabase Dashboard (Backend).

Code snippet

VITE_SUPABASE_URL=your_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_key
GEMINI_API_KEY=your_api_key
Run Development Server:

Bash

npm install && npm run dev
👨‍💻 About The Developer
Muzammil Ahmed AI / Web Development Enthusiast

🔗 LinkedIn: Connect with me

🐙 GitHub: @MuzammilBaloch-22

📧 Email: muzambaloch22@gmail.com

