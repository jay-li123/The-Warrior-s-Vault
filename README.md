# 🗡️ The Warrior's Vault

A full-stack **PERN application** forged with strength and precision.  
The Warrior’s Vault is your digital stronghold — blending modern web technologies, secure APIs, and a sleek UI built for managing your inventory like a true warrior.  

---

## ⚡ Highlights

- 🌟 **Tech stack**: PostgreSQL + Express + React + Node (PERN)  
- 🎨 **UI Styling**: TailwindCSS + DaisyUI + Lucide Icons  
- ⚔️ **Global State Management** with Zustand  
- 🛡️ **Rate Limiting & Bot Detection** with [Arcjet](https://arcjet.com/)  
- 🐞 **Error Handling** on both server and client  
- 💾 **Database**: Neon serverless PostgreSQL  
- 🎨 **Theme Switching** (light/dark + multiple DaisyUI themes)  

---

## 🛠️ Features

### Backend
- RESTful CRUD API (`/api/products`)  
- Neon PostgreSQL integration  
- Secure middlewares: Helmet, CORS, Arcjet, Morgan  
- Automatic database table creation  

### Frontend
- Modern responsive UI with **DaisyUI + TailwindCSS**  
- Product management: add, edit, delete, view  
- Realtime state sync with Zustand  
- Toast notifications (`react-hot-toast`)  
- Light/Dark mode & theme selector  
- Smooth UX with modals, loaders, and empty-state screens  

---

## 🔧 Setup

### 1. Clone the repository:
```
git clone https://github.com/your-username/the-warriors-vault.git
```

### 2. Create a .env file in the root:
  ```
  PORT=3000
  
  PGUSER=...
  PGPASSWORD=...
  PGHOST=...
  PGDATABASE=...
  
  ARCJET_KEY=...
  ARCJET_ENV=development
  ```

### 3. Run the API
  ```
  npm run dev
  ```

### 4. Run the frontend
  ```
  cd frontend
  npm run dev
  ```

---

## 📜 Inspiration
This project was built upon the awesome PERN Crash Course by Codesistency.
