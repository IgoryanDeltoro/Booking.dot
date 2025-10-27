# My First Vue Project  
A simple & fun pet project built with Vue 3 + Vite + Vercel deployment.

## 🚀 Live Demo  
[https://my-first-vue-project-gamma.vercel.app/go-home/](https://my-first-vue-project-gamma.vercel.app/go-home/)

## 🧠 Project Purpose  
This project is built for learning and experimentation. My goals:  
- Explore the fundamentals of Vue.js (version 3) with the `<script setup>` syntax.  
- Get hands‑on with Vite as a build tool and dev‑server.  
- Set up routing, simple views/components, and deploy to Vercel for a live preview.  
- Make a lightweight, clean starter project that I can extend later as I learn more.

## 🛠 Tech Stack  
- Vue 3 (Composition API with `<script setup>`)  
- Vite (fast build & dev tooling)  
- SCSS for styling (optional)  
- Routing (Vue Router)  
- Deployed to Vercel (automatic builds + hosting)  
- Project structure scaffolded from the “Vue 3 + Vite” template.

## 📁 Project Structure (excerpt)  
```
my‑first‑vue-project/
├─ public/
│   └─ index.html
├─ src/
│   ├─ components/      ← reusable UI components  
│   ├─ views/           ← route‑level views (e.g., GoHome.vue)  
│   ├─ router/          ← routing definitions  
│   ├─ App.vue  
│   └─ main.js
├─ .vscode/
├─ package.json  
├─ vite.config.js  
└─ README.md
```

## ✅ Features & Learning Highlights  
- Basic navigation/routing (e.g., `/go‑home/`)  
- Use of single‑file components (.vue) with the `<script setup>` syntax  
- Lightweight, clean code for easy extension  
- Deployment pipeline to Vercel with minimal config (via `vercel.json`)  
- Good starter for building further (adding new routes, state management, UI frameworks, etc.)

## 🔍 How to Run Locally  
1. Clone the repository  
   ```bash
   git clone https://github.com/IgoryanDeltoro/my-first-vue-project.git
   cd my-first-vue-project
   ```  
2. Install dependencies  
   ```bash
   npm install
   ```  
3. Start the development server  
   ```bash
   npm run dev
   ```  
   Visit `http://localhost:3000` (or whichever port Vite uses) to view the app.  
4. Build for production  
   ```bash
   npm run build
   ```  
5. (Optional) Preview the production build locally  
   ```bash
   npm run preview
   ```  

## 🎯 Next Steps / What’s Coming  
Since this is a pet‑/learning project, some ideas for future enhancements:  
- Add additional routes/views (e.g., About, Contact, Dashboard)  
- Introduce a component library or UI framework (e.g., Tailwind CSS, Vuetify)  
- Manage state via Pinia (or Vuex) for more complex apps  
- Add unit tests / end‑to‑end tests (e.g., Vitest + Cypress)  
- Explore advanced Vue features: custom directives, plugins, composition functions  
- Improve styling and responsiveness for mobile / desktop

## 📄 License  
This project is open‑source and available under the [MIT License](LICENSE) (if you choose to add a LICENSE file).

---

> **Tip:** Treat this as a sandbox—feel free to play around, break things, learn, and rebuild.

Thanks for checking out my project! 👋  
Feel free to drop me a message if you want to collaborate or learn together.

