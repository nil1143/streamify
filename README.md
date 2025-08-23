# Streamify

Live demo: https://streamify-bmad.onrender.com/

Streamify is a MERN‑stack language‑exchange web application that helps learners discover, connect, and practice with language partners. Sign up and complete a short onboarding profile, browse recommended matches, send and manage friend requests, chat in real time via Stream Chat, and create shareable video‑call links for practice sessions.


## 📌 Table of contents
- [📃 About](#about)
    - [Summary](#summary)
    - [Key Features](#key-featueres)
   - [Tech Stack](#tech-stack)
- [🔅 Design](#design)
    - [Themes](#themes)
    - [Fonts & UI](#fonts-&-ui)
    - [Responsive view](#responsive-view)
- [💁 User Stories](#user-stories)
- [📷 Screenshoots](#screenshoots)
    - [Desktop](#desktop)
    - [Mobile](#mobile)
- [🔧 Deployment](#deployment)
    - [.env Setup](#dotenv-setup)
    - [Run the Backend](#run-the-backend)
    - [Run the Frontend](#run-the-frontend)
- [📬 Contact](#contact)


## 📃 About

#### Summary
 React app (Vite) built on the MERN stack with a production-ready backend. Frontend focuses: discover language partners, friend-request flow, real-time chat (Stream Chat), theming, and responsive UI.

#### Key features
- Email/password auth + onboarding
- Discover recommended partners and send friend requests
- Notifications: accept / decline friend requests
- Real-time chat powered by Stream Chat and sendable video-call links
- Theme selector (Zustand) and responsive layout (Tailwind + DaisyUI)

### Tech Stack

- Frontend: React (Vite) 

    ![React](https://img.shields.io/badge/React-%20-61DAFB?logo=react)
![Vite](https://img.shields.io/badge/Vite-%20-646cff?logo=vite)
- Styling: TailwindCSS (+ DaisyUI) 

    ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%20-06B6D4)
![DaisyUI](https://img.shields.io/badge/DaisyUI-%20-7839E6)
- Backend: Node.js, Express

    ![Node.js](https://img.shields.io/badge/Node.js-%20-339933?logo=node.js)
![Express](https://img.shields.io/badge/Express-%20-000000?logo=express)
- Database: MongoDB (Mongoose / Atlas)

    ![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb)
- State / data: Zustand, React Query

    ![Zustand](https://img.shields.io/badge/Zustand-%20-111111)
![React Query](https://img.shields.io/badge/React%20Query-%40tanstack-FF4154?logo=tanstack)

- Networking: Axios

    ![Axios](https://img.shields.io/badge/Axios-%20-5A29E4?logo=axios)
- Realtime chat/calls: Stream (Chat + Video SDK)

    ![GetStream](https://img.shields.io/badge/GetStream-Chat-FF6D00?logo=getstream)









## 🔅 Design

#### Themes
- Multiple theme presets selectable via the ThemeSelector.
- Active theme persisted in localStorage (`streamify-theme`) via Zustand store.
- Theme drives global background and component accents (applied to body/main container).

#### Fonts & UI
- Tailwind + DaisyUI components for a clean, responsive UI.
- Consistent component spacing, rounded cards, and accessible controls.

#### Responsive view
- Layout uses a sidebar + main column pattern.
- Pages adapt to mobile using stacked layout and collapsible nav.
- Home discovery grid collapses to a single column on narrow viewports.

---

## 💁 User stories

| As a... | I want... | So that... |
|---|---|---|
| New user | I can sign up and complete onboarding | My profile (languages, location, avatar) is set and recommended partners show correctly |
| Logged-in user | I can browse recommended partners on Home | I can find good language exchange matches |
| Logged-in user | I can send a friend request | I can connect and start chatting with a partner |
| Recipient | I can accept or decline friend requests in Notifications | I can manage my connections |
| Connected users | I can open a chat and send messages / call links | We can coordinate practice sessions (video calls) |
| Any user | I can switch themes | The UI matches my preferred visual style and persists across sessions |
| Developer | I can run the app locally and inspect the API | I can reproduce and test flows before deployment |


---

## 📷 Screenshots

### Desktop
- #### Home / Discovery  
  ![Homepage](/frontend/public/readme/homepage2.png)

- #### Signup / Onboarding  
  ![Signup](/frontend/public/readme/signup.png) ![Login](/frontend/public/readme/login.png) ![Onboarding](/frontend/public/readme/onboarding.png)

- #### Notifications
  ![Notifications](/frontend/public/readme/notifications.png)

- #### Chat / Video call
  ![Chat](/frontend/public/readme/chat.png)
  ![Video Call](/frontend/public/readme/call.png)

- #### Theme examples  
  ![Theme 1](/frontend/public/readme/theme1.png) ![Theme 2](/frontend/public/readme/theme2.png)

### Mobile
- #### Signup
  ![Mobile](/frontend/public/readme/mobile.png)

- #### Homepage
  ![Mobile2](/frontend/public/readme/mobile-2.png)

- #### Notifications
  ![Mobile3](/frontend/public/readme/mobile-3.png)

---

## 🔧 Deployment
### 🧪 .env Setup

#### Backend (`/backend`)

```
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

#### Frontend (`/frontend`)

```
VITE_STREAM_API_KEY=your_stream_api_key
```

---

### 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

### 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📬  Contact
<div align="center">
Send me an email
<br><br>

```
tnil1143@gmail.com
```



or check my profiles

[![Github][Github]][Github-url] [![LinkedIn][LinkedIn]][Linkedin-url]
</div>

[LinkedIn]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[LinkedIn-url]: https://www.linkedin.com/in/tomasz-nilipiuk-b5b88a239/
[Github]: https://img.shields.io/badge/github-black.svg?style=for-the-badge&logo=github&colorB=333
[Github-url]: https://github.com/nil1143