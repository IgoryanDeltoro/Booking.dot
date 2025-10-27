#Booking.dot — Booking Platform (Frontend)

A pet project built with **Vue 3 + Vite**, serving as the **frontend** for a small booking application.  
This app helps users find and book apartments online, manage profiles, and interact with listings in real time.

---

## 🚀 Live Demo  
[https://my-first-vue-project-gamma.vercel.app/go-home/](https://my-first-vue-project-gamma.vercel.app/go-home/)

## 🧩 Related Backend Repository  
The backend REST API for this project:  
👉 [booking-cli](https://github.com/IgoryanDeltoro/booking-cli)

---

## 🧠 Project Purpose  

This project was created to:
- Learn **Vue 3** using the Composition API and `<script setup>` syntax.  
- Build a full-stack app by connecting this frontend to a **Node.js CLI/Express-based backend**.  
- Implement modern app features like search, pagination, user authentication, and apartment ratings.  
- Deploy a production-ready app to **Vercel**.

---

## 🛠 Tech Stack  

**Frontend**
- Vue 3 + Vite  
- Vue Router  
- Pinia (for state management)  
- Axios (for API requests)  
- Tailwind CSS / SCSS (for styling)

**Backend**
- Node.js + Express  
- MongoDB or PostgreSQL (for data persistence)  
- JWT Authentication  
- Deployed on Render / Vercel (via [booking-cli](https://github.com/IgoryanDeltoro/booking-cli))

---

## 💡 Features  

### 🏠 Apartment Listings
- Browse available apartments with photos, price, and location.  
- Pagination for easy navigation across many listings.  
- Dynamic search bar to filter apartments by city, price range, or rating.

### 👤 User Accounts
- User registration and login (JWT-based).  
- Persistent sessions with token-based authentication.  
- Editable user profile.

### ⭐ Ratings and Reviews
- Each user can rate an apartment from 1–5 stars.  
- See average ratings and total number of reviews.  
- Store and view your booking history.

### 🕓 Booking History
- View a list of all past and active bookings.  
- Sort bookings by date or location.  
- Cancel or modify bookings (if allowed by API).

### 🔍 Smart Searching & Pagination
- Search apartments instantly with live results.  
- Paginated results ensure smooth performance even with large datasets.

### 🧾 Responsive UI
- Fully responsive design for desktop and mobile.  
- Minimal and modern layout for pleasant user experience.

---

## 📁 Project Structure  

