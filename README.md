<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=6366F1&background=00000000&center=true&vCenter=true&width=700&lines=NagrikSetu;Report+%26+Track+Civic+Issues;Empowering+Communities+%26+Authorities" alt="Typing SVG" />
</div>

<div align="center">
  <h3>🛣️ A community-driven platform to report and track civic issues in your city 🛣️</h3>
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100">
</div>

---

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

<h3 align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#installation">Installation</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#team">Team</a>
</h3>

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">
</div>

## 🚀 **About NagrikSetu**

NagrikSetu is a comprehensive, community-driven platform that empowers citizens to report civic issues and helps authorities track and resolve them efficiently. From potholes and streetlight faults to sanitation problems, NagrikSetu bridges the gap between citizens and municipal services with transparency, real-time updates, and an admin dashboard.

### ✨ **Key Highlights**

- 📱 **User-Friendly Interface** - Intuitive reporting system
- 🗺️ **Interactive Map** - Visual representation of reported issues
- 👥 **Community Driven** - Real-time updates from local residents
- 📊 **Admin Dashboard** - Comprehensive management tools
- 🔄 **Real-time Updates** - Track issue resolution progress

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

## 🎯 **Features**

<div align="center">

| Feature                  | Description                                  |
| ------------------------ | -------------------------------------------- |
| 🚨 **Issue Reporting**   | Easy-to-use form for reporting road problems |
| 🗺️ **Interactive Map**   | Visual map showing all reported issues       |
| 📊 **Admin Dashboard**   | Complete management system for authorities   |
| 👤 **User Dashboard**    | Personal tracking of submitted reports       |
| 🌙 **Dark/Light Mode**   | Toggle between themes for better UX          |
| 📱 **Responsive Design** | Works seamlessly on all devices              |

</div>

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">
</div>

## 🛠️ **Tech Stack**

<div align="center">

| Category             | Technologies                                       |
| -------------------- | -------------------------------------------------- |
| **Frontend**         | React 18, TypeScript, Vite                         |
| **Styling**          | Tailwind CSS, shadcn/ui                            |
| **State Management** | React Hooks, Context API                           |
| **Backend**          | Node.js, Express.js                                |
| **Database**         | MongoDB (Mongoose)                                 |
| **Realtime**         | Socket.io                                          |
| **Maps**             | Mapbox                                             |
| **Media**            | Cloudinary (resolution images)                     |
| **Build Tool**       | Vite                                               |
| **Package Manager**  | npm / bun                                          |
| **Deployment**       | Vercel/Netlify (Frontend), Render/Heroku (Backend) |

</div>

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

## 📁 **Project Structure**

```
NagrikSetu/
├── Frontend/
│   ├── public/
│   │   ├── logo.png
│   │   ├── manifest.webmanifest
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   ├── AdminDashboard.tsx
│   │   │   ├── UserDashboard.tsx
│   │   │   ├── ReportPage.tsx
│   │   │   └── ui/            # shadcn/ui components
│   │   ├── hooks/
│   │   ├── services/
│   │   └── pages/
│   ├── package.json
│   └── vite.config.ts
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── server.js
│   └── package.json
└── README.md
```

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">
</div>



---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

## ⚙️ **Installation & Local Setup**

Follow these steps to run NagrikSetu locally.

1. Clone the repository

```
git clone https://github.com/Divyansh8843/NagrikSetu.git
cd NagrikSetu
```

2. Backend setup (`backend/`)

```
cd backend
npm install
cp config.env.example .env   # Or set environment variables per your OS
```

Required backend environment variables (example):

```
PORT=5000
MONGO_URI=mongodb://localhost:27017/nagriksetu
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
MAPBOX_TOKEN=...
CLIENT_URL=http://localhost:5173
```

Start backend in dev mode:

```
npm run dev
```

3. Frontend setup (`Frontend/`)

```
cd ../Frontend
npm install
cp env.example .env           # Or set Vite env vars
```

Common frontend environment variables:

```
VITE_API_BASE_URL=http://localhost:5000/api
VITE_MAPBOX_TOKEN=...
```

Start frontend:

```
npm run dev
```

The app should be available at `http://localhost:5173` (frontend) and `http://localhost:5000` (backend).

## 🚀 **Deployment**

- Frontend: Deploy `Frontend/` to Vercel or Netlify. Set `VITE_API_BASE_URL` to your backend URL.
- Backend: Deploy `backend/` to Render/Heroku/Railway. Set environment variables as above and allow CORS from your frontend domain.

## 🔌 **API Overview**

Key routes (prefix `/api`):

- `POST /reports` — Create report
- `GET /reports` — List reports (filtering supported)
- `GET /reports/:id` — Report details
- `PATCH /admin/reports/:id/status` — Update status (admin)
- `PATCH /admin/reports/:id/assign` — Assign contractor (admin)
- `GET /reports/stats/response-times` — Resolution time metrics

For more, see `backend/routes/` and `backend/controllers/`.

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="1000">
</div>

## 🤝 **Contributing**

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
  <h3>🌟 Star this repository if you found it helpful! 🌟</h3>
  <img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="Built with Love">
  <img src="https://forthebadge.com/images/badges/made-with-typescript.svg" alt="Made with TypeScript">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">
</div>
