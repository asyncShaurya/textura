<div align="center">

# 🎨 Textura
### AI-Powered Text-to-Image Generation Platform

<p align="center">
Transform text prompts into stunning AI-generated images with a modern full-stack web application featuring secure authentication, credit-based usage, and seamless user experience.
</p>

<p align="center">

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb)
![JWT](https://img.shields.io/badge/JWT-Authentication-black?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Deployment-Vercel-black?style=for-the-badge&logo=vercel)

</p>

### 🚀 Generate • Download • Share • Create

</div>

---

# 📖 About

**Textura** is a modern AI-powered SaaS application that converts text prompts into high-quality images using artificial intelligence.

The platform allows users to securely register, generate AI images, manage credits, purchase additional credits, and download generated images through an intuitive and responsive interface.

Built using the **MERN Stack**, the application follows a clean **MVC Architecture**, making it scalable, modular, and production-ready.

---

# ✨ Features

- 🤖 AI Image Generation
- 🎨 Convert Text into Images
- 🔐 JWT Authentication
- 👤 User Registration & Login
- 💳 Credit-Based System
- 💰 Purchase Additional Credits
- 📥 Download Generated Images
- 🖼 Image Gallery
- 📱 Fully Responsive UI
- ⚡ RESTful APIs
- ☁️ Cloud Deployment
- 🛡 Protected Routes
- 📂 MVC Backend Architecture

---

# 🌟 Key Highlights

- ⚡ MERN Stack Architecture
- 🤖 AI-powered Image Generation
- 🛡 Secure JWT Authentication
- 💳 Credit Management System
- 🏗 MVC Backend Architecture
- 🌐 REST API Design
- 📱 Responsive User Interface
- 🚀 Production Deployment on Vercel
- ☁️ Cloud Storage Integration
- 🔄 Modular & Scalable Codebase

---

# 🛠 Tech Stack

| Frontend | Backend | Database | Authentication |
|-----------|----------|----------|----------------|
| React.js | Node.js | MongoDB | JWT |
| Vite | Express.js | Mongoose | Protected Routes |
| Context API | REST APIs | MongoDB Atlas | Middleware |

---

# 🏛️ System Design

The application follows a modern client-server architecture where the React frontend communicates with the Express backend through REST APIs. The backend handles authentication, credit management, AI image generation, and stores user data in MongoDB.

```text
                    ┌─────────────────────┐
                    │        User         │
                    └──────────┬──────────┘
                               │
                               ▼
                 ┌────────────────────────┐
                 │ React + Vite Frontend  │
                 └──────────┬─────────────┘
                            │
                     REST API Requests
                            │
                            ▼
                  ┌─────────────────────┐
                  │ Express.js Backend  │
                  └──────────┬──────────┘
                             │
      ┌──────────────────────┼─────────────────────┐
      ▼                      ▼                     ▼
Authentication         Image Controller     Credit System
      │                      │                     │
      └──────────────────────┼─────────────────────┘
                             ▼
                        MongoDB Atlas
                             │
                             ▼
                     AI Image Generation API
```

---

# 🔄 Image Generation Workflow

```text
User enters prompt
        │
        ▼
React Frontend
        │
        ▼
Authentication Check
        │
        ▼
Verify User Credits
        │
        ▼
Send Prompt to Backend
        │
        ▼
AI Image Generation API
        │
        ▼
Generated Image
        │
        ▼
Save Transaction
        │
        ▼
Display & Download Image
```

---

# 💳 Credit System Workflow

```text
User
 │
 ▼
Purchase Credits
 │
 ▼
Payment Gateway
 │
 ▼
Payment Verification
 │
 ▼
Update MongoDB
 │
 ▼
Credits Added Successfully
```

---

# 📂 Project Structure

```text
textura/

├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── server/
│   ├── config/
│   │   └── mongodb.js
│   │
│   ├── controllers/
│   │   ├── imageController.js
│   │   └── userController.js
│   │
│   ├── middlewares/
│   │   └── auth.js
│   │
│   ├── models/
│   │   ├── userModel.js
│   │   └── transactionModel.js
│   │
│   ├── routes/
│   │   ├── imageRoutes.js
│   │   └── userRoutes.js
│   │
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

# 🏗 MVC Architecture

```text
             Client Request
                    │
                    ▼
                Routes Layer
                    │
                    ▼
            Controller Layer
                    │
                    ▼
              Business Logic
                    │
                    ▼
               Model Layer
                    │
                    ▼
                MongoDB Atlas
```

---

# 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/asyncShaurya/textura.git
```

---

### Frontend

```bash
cd client

npm install

npm run dev
```

---

### Backend

```bash
cd server

npm install

npm start
```

---

# ⚙️ Environment Variables

### Backend (.env)

```env
MONGODB_URI=

JWT_SECRET=

CLIPDROP_API_KEY=

CURRENCY=

PAYMENT_GATEWAY_SECRET=
```

### Frontend (.env)

```env
VITE_BACKEND_URL=
```

---

# 📡 REST API

| Endpoint | Description |
|----------|-------------|
| POST /register | Register User |
| POST /login | Login User |
| GET /profile | User Profile |
| POST /generate | Generate AI Image |
| POST /buy-credit | Purchase Credits |
| GET /transactions | Transaction History |

---

# 🎯 Learning Outcomes

This project helped me gain practical experience with:

- MERN Stack Development
- MVC Architecture
- JWT Authentication
- REST API Development
- MongoDB & Mongoose
- AI API Integration
- Payment Workflow
- Context API
- State Management
- Cloud Deployment
- Responsive UI Development
- Secure Backend Development

---

# 🔮 Future Improvements

- Image History
- Favorites Collection
- AI Style Selection
- Multiple Image Variations
- Social Sharing
- Prompt History
- Image Editing
- Team Workspace
- Dark Mode
- Admin Dashboard
- Analytics
- Docker Deployment

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

## Shaurya Singh

Final Year B.Tech Computer Science Engineering Student

### Interests

- Full Stack Development
- Backend Engineering
- Artificial Intelligence
- Cloud Computing
- Web3
- System Design

### GitHub

https://github.com/asyncShaurya

### LinkedIn

https://linkedin.com/in/shaurya-singh-2811b432a

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

It motivates me to continue building impactful open-source projects.

---

# 📄 License

This project is licensed under the MIT License.
