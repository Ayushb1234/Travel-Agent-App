# 🌍 Multi-Agent Travel Planner

AI-powered **Travel Planning App** that generates personalized itineraries, optimizes budgets, and provides hotel & activity recommendations using **multi-agent collaboration**.  
Built with a modern **React + TypeScript frontend** and a **FastAPI backend**, the app demonstrates how AI can make travel planning effortless and smarter.

---

## ✨ Key Features
- 🔮 **AI-Powered Itinerary Planning** – Suggests daily trip schedules tailored to preferences.
- 💰 **Smart Budget Optimization** – Calculates per-day and per-person costs, ensures trips stay under budget.
- 🏨 **Hotel Recommendations** – Lists multiple hotel options with prices and ratings.
- 📍 **Interactive Map (MapTiler/Leaflet ready)** – Visualize destinations and accommodations.
- ⚡ **Personalized Preferences**
  - Must-visit places
  - Avoided areas
  - Pace of trip (relaxed/normal/fast)
  - Food & stay preferences
- 📊 **Visual Budget Breakdown** – Progress bars & daily totals.
- 🎨 **Modern Responsive UI** – Gradient hero section, navbar, and analytics footer.
- 🖥️ **Fullstack Architecture** – Clean separation between **frontend** and **backend**.

---

## 🛠 Tech Stack
### Frontend
- ⚛️ **React + TypeScript**
- 🎨 **Custom CSS + Tailwind-inspired styling**
- 🗺 **MapTiler API (Leaflet-ready integration)**
- 🧰 **Lucide-React** icons

### Backend
- 🚀 **FastAPI** (Python) – RESTful API
- 📦 **Uvicorn** – ASGI server
- 🧮 AI-powered **multi-agent orchestration** (custom logic for trip planning)

### Dev Tools
- ⚙️ **Vite** for frontend build
- 🔑 **Environment variables (.env)** for API keys and config

---

## 📂 Project Structure


---

## 🚀 Getting Started

### 1️⃣ Clone the Repo
```bash
git clone https://github.com/Ayushb1234/Travel-agent-app.git
cd Travel-Agent-app
```


2️⃣ Backend Setup (FastAPI)
```bash
cd Travel_planner_
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
```

3️⃣ Frontend Setup (React + Vite)
```bash
cd ../Travel_planner_frontend
npm install
npm run dev
```



📸 Screenshots & Demo
-------------------------

Replace with your own screenshots later.

Landing Page:
<img width="1902" height="762" alt="image" src="https://github.com/user-attachments/assets/0f225a99-53a6-4551-9798-6c0be1e92e42" />
<img width="1139" height="866" alt="image" src="https://github.com/user-attachments/assets/e7e13551-a73b-4328-9ad4-96f65eb710ec" />
<img width="974" height="499" alt="image" src="https://github.com/user-attachments/assets/4ba5b615-5ed8-4323-9c6f-edf31c567241" />
<img width="961" height="638" alt="image" src="https://github.com/user-attachments/assets/29f2819e-ba97-491c-9cd5-c69440943cae" />


🎥 Demo Video: https://drive.google.com/file/d/1NsiTKFo6JeVdzGDuhpMLTWXeBU5PXiT-/view?usp=sharing

🌐 Live Deployment: Soon to be uploaded...


Problems & Failures Faced
--------------------------

During development, several issues were encountered:

❌ Environment Variables Not Loading – Fixed by adding .env and using VITE_ prefix for frontend.

❌ CORS Errors – Resolved by enabling CORS middleware in FastAPI backend.

❌ Map API Key Issues – Required creating a free MapTiler key and configuring correctly.

❌ Frontend Alignment – Hero section & navbar required redesign for clean UX.

❌ Budget Calculations – Initially inconsistent; fixed by normalizing per-day and per-person logic.

❌ Error Handling in API – Backend errors returned raw logs; added structured error messages.


🔮 Future Advancements
---------------------------

🧭 Full Interactive Map Integration (Leaflet/Mapbox with hotel markers).

🤝 Collaboration Mode – Plan trips with friends in real-time.

📱 Mobile App (React Native/Expo) version.

🌐 Multi-Language Support for global users.

📊 Advanced Analytics – Recommend best travel seasons, activities, and costs.

☁️ Cloud Deployment with CI/CD (Docker, AWS/GCP).

🤝 Contributing
----------------
Pull requests are welcome. Please open an issue first to discuss changes.
