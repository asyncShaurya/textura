✨ What is Textura?

Textura explores clean UI patterns on the client and a simple service layer on the server. The goal is a fast, approachable codebase you can run locally in minutes and deploy quickly.

🧭 Project Structure
textura/
├─ client/ # Frontend (React + Tailwind UI)
└─ server/ # Backend (Node.js-based service layer)
> The repository is predominantly JavaScript, with a small amount of HTML/CSS.

🛠 Tech Stack

**Frontend**
- React (SPA approach)
- Tailwind CSS (utility-first styling)
- Vite or CRA-style dev server (typical local workflow)

**Backend**
- Node.js (plain JS service)
- REST-style endpoints (lightweight)

**Deployment**
- Vercel (frontend)
> Note: The server is kept minimal and can evolve into Express/Fastify/Koa as needed.

 🚀 Getting Started

### 1) Clone the repository
git clone https://github.com/asyncShaurya/textura.git
cd textura

2) Run the frontend
cd client
npm install
npm run dev
# then open the printed localhost URL

3) Run the backend
cd server
npm install
npm run dev
# typical default ports are 5000/8080 — adjust as needed

📦 Scripts (common patterns)
# client
npm run dev       # start local dev server
npm run build     # production build
npm run preview   # preview production build

# server
npm run dev       # start server with watch/reload
npm start         # start server (prod)
