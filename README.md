# 🥗 Smart Food Connect

**Smart Food Connect** is a web-based platform designed to reduce food waste and fight hunger (aligned with **UN SDG 2: Zero Hunger**).  
It connects donors who have surplus food (restaurants, individuals, hotels, etc.) with nearby recipients (NGOs, shelters, schools, or individuals in need).

---

## 🚀 Features
- 🥙 **Post Donations:** Donors can submit food details, quantity, and pickup location.  
- 📍 **View Donations:** Recipients can view available donations in real time.  
- 🔍 **Search & Filter:** Donations can be filtered by location or type of food.  
- 🕐 **Auto-Expiry:** Donations expire after a set time to ensure food safety.  
- 🌐 **MongoDB Backend:** All donation data is stored securely in MongoDB.  
- ⚡ **React Frontend:** Clean, fast, and responsive interface.

---

## 🧰 Tech Stack
**Frontend:** React.js (Vite or CRA)  
**Backend:** Node.js + Express.js  
**Database:** MongoDB  
**Styling:** Tailwind CSS  
**Version Control:** Git + GitHub  

---

## 📁 Project Structure
Smart_Food_Connect/
│
├── backend/
│ ├── index.js
│ ├── models/
│ │ └── Donation.js
│ ├── routes/
│ │ └── donations.js
│ ├── package.json
│ └── .env
│
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ ├── api.js
│ │ ├── components/
│ │ │ ├── DonationForm.js
│ │ │ └── DonationList.js
│ ├── package.json
│ └── public/
│
└── README.md

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Smart_Food_Connect.git
cd Smart_Food_Connect
2️⃣ Setup Backend
cd backend
npm install


Create a .env file in /backend and add:

PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/smart_food_connect


Run the backend:

npm run dev

3️⃣ Setup Frontend
cd ../frontend
npm install
npm start

🌍 Live Demo

Frontend: http://localhost:3000

Backend API: http://localhost:5000/api/donations

🧪 Example Use

A restaurant posts: “10 plates of rice, ready before 7 PM.”

A local NGO checks available donations and contacts the donor.

The platform logs the transaction and auto-expires old listings.
👨‍💻 Author

Philip Karisa
Graphic Designer | web developer | Electrical Engineering Student
📧 Email: karisaphilip@gmail.com
📱 Phone: 0797585552
