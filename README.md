# 📹 VidMeet

**VidMeet** is a full-stack, real-time video calling platform built with **React**, **Node.js**, **Express**, and **Socket.IO**. It supports **audio/video calls**, **screen sharing**, **chat**, and more — all in your browser.

---

## 🚀 Features

* ✅ Real-time audio/video calling
* ✅ Screen sharing support
* ✅ Instant messaging during calls
* ✅ Unique room codes for secure meetings
* ✅ Smooth UI with light/dark mode
* ✅ Responsive design for mobile and desktop

---


<img width="1680" alt="Image" src="https://github.com/user-attachments/assets/f1a15dd0-6048-4e29-8d22-f67605f3af4a" />
<img width="1678" alt="Image" src="https://github.com/user-attachments/assets/b7595320-89d0-430e-8782-d8d093d707b7" />
<img width="1680" alt="Image" src="https://github.com/user-attachments/assets/c72fbcae-7da0-4ec9-a997-4dd8ed183262" />

## 💠 Tech Stack

* **Frontend**: React + Tailwind CSS
* **Backend**: Node.js + Express
* **WebSocket**: Socket.IO
* **Hosting**: Vercel (frontend) & Render (backend)
* **Other Tools**: WebRTC, HTTPS, Vite

---

## 📁 Folder Structure

```
/
├── client/       → React frontend (Vite)
├── server/       → Express + Socket.IO backend
├── .gitignore
├── README.md
└── ...
```

---

## 🔧 Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/VidMeet.git
cd VidMeet
```

---

### 2. Setup Backend (server)

```bash
cd server
npm install
```

#### 🔑 Create `.env` in `/server`

```env
PORT=8000
CLIENT_ORIGIN=http://localhost:5173
```

#### ▶️ Start the server

```bash
npm start
```

---

### 3. Setup Frontend (client)

```bash
cd ../client
npm install
```

#### 🌐 Create `.env` in `/client`

```env
VITE_SOCKET_SERVER_URL=https://your-render-backend-url.com
```

#### ▶️ Start the frontend

```bash
npm run dev
```

---

## 🌐 Deployment

* **Frontend**: Deployed on [Vercel](https://vercel.com)
* **Backend**: Deployed on [Render](https://render.com)

Make sure to update your `.env` files accordingly before deploying.

---

## 📸 Screenshots

| Video Call                                  | Screen Share                                    | Chat                            |
| ------------------------------------------- | ----------------------------------------------- | ------------------------------- |
| ![Video Call](./screenshots/video-call.png) | ![Screen Share](./screenshots/screen-share.png) | ![Chat](./screenshots/chat.png) |

---

## 🙇‍♂️ Author

**Joydeep Hans**
[GitHub](https://github.com/JoydeepHans)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
