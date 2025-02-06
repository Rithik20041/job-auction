# Reverse Auction Job Board

## 📌 Project Overview
This project flips the traditional hiring process by allowing **employers to bid** on candidates instead of candidates applying for jobs. This ensures that skilled professionals receive the best possible offers while companies compete for talent.

## 🎯 Project Objective
- **Revolutionize hiring** by creating a competitive marketplace for talent.
- **Empower job seekers** to get better job offers.
- **Help companies** find top talent quickly through bidding.
- **Facilitate real-time** job offers using WebSockets.

---

## 🔄 Workflow
### **User Roles**
1. **Admin** – Manages users, bids, and disputes.
2. **Candidate (Customer)** – Creates a profile and receives job bids.
3. **Employer (Customer)** – Bids on candidates for hiring.

### **Navigation Flow**
**🔹 Public Users (Before Login)**
- Home → Login → Register → Dashboard (based on role)

**🔹 Candidate Flow**
1. Login → Complete Profile → Wait for Bids
2. View & Accept Bids →  Get Hired

**🔹 Employer Flow**
1. Login → Browse Candidates → Place Bids
2. Track Bids → Chat with Candidates → Hire

**🔹 Admin Flow**
1. Login → View Site Overview → Manage Users & Bids

---

## 📄 Pages & Navigation
### **1️⃣ Authentication Pages (All Users)**
✅ **Login / Signup Page** – Google OAuth & Email-based registration  

### **2️⃣ Candidate Pages (Customer Role)**
✅ **Dashboard** – View job bids, accepted jobs, & messages  
✅ **Profile Page** – Edit skills, experience, expected salary  
✅ **Bid History Page** – View past and current offers  
✅ **Settings Page** – Manage account & notifications  

### **3️⃣ Employer Pages (Customer Role)**
✅ **Dashboard** – Browse candidates, view active bids, manage hiring  
✅ **Candidate Listings Page** – Filter by skills, experience, salary  
✅ **Bid Placement Page** – Enter an offer & bid on a candidate  
✅ **Bid History Page** – Track ongoing & past bids  
✅ **Settings Page** – Manage company profile & account  

### **4️⃣ Admin Pages (Admin Role)**
✅ **Admin Dashboard** – Overview of bids, users & disputes  
✅ **User Management Page** – View, delete, or ban users  
✅ **Bid Monitoring Page** – Track ongoing and past bids  

---

## 🚀 Tech Stack
**Frontend:** React.js/Next.js, Tailwind CSS, WebSockets (Socket.io)  
**Backend:** Node.js with Express.js  
**Database:** MongoDB/PostgreSQL  
**Authentication:** JWT, OAuth (Google/LinkedIn Login)  
**Hosting:** Vercel (Frontend), Render/Fly.io (Backend)  

