# Dr. Mayada Clinic Management System 🏥

**A Comprehensive Full-Stack Healthcare Management & Smart Booking Platform**

🔗 **[Live Patient Portal](booking.drmayadaclinic.com)**

## 📌 Project Overview
An advanced, production-grade clinic management system designed to handle complex scheduling constraints, real-time session tracking, and financial operations. Built with a focus on high security, scalable architecture, and seamless user experience across mobile and web interfaces.

---

## Key Features & System Architecture

### 1. Hybrid Deployment Architecture (Security First)
To ensure maximum patient data privacy and financial record security, the system utilizes a **Hybrid Deployment Model**. The core backend and database are hosted on a secure local workstation within the clinic, connected to a cloud gateway via Cloudflare Tunnels to serve the online booking portal.

### 2. Smart Booking Engine (Conflict Resolution)
Developed a highly optimized scheduling algorithm that eliminates overlapping appointments. The engine simultaneously validates:
* Doctor shift availability and existing appointments.
* Shared physical room occupancy limits.
* Variable service durations.

### Smart Booking Interface & Calendar Allocation
<p align="center">
  <img src="https://github.com/user-attachments/assets/d584c251-232c-4898-871e-6f2bb9e8edb4" width="200" />
  <img src="https://github.com/user-attachments/assets/ab8c5e22-f2e8-4292-8fc4-b99fee1eb8f0" width="200" />
  <img src="https://github.com/user-attachments/assets/a0bbbde4-0828-4d25-8ee9-880f243b1791" width="200"/>
  <img src="https://github.com/user-attachments/assets/371e73fe-56c8-495f-be6d-e06497aa7ec9" width="200" />
  

### 3. Point-of-Sale (POS) & Patient Wallet
Integrated a comprehensive financial system for the receptionist desk, featuring:
* A digital Patient Wallet for automated change retention and future billing.
* Real-time cash and debt tracking.
* Doctor commission and salary calculations based on daily revenue.

### Receptionist POS, Wallet & Patient Management
<p align="center">
  <img src="https://github.com/user-attachments/assets/d03e0513-8685-4429-8096-77d818a436c1" width="800" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/763b643a-7545-4c58-9c12-efbd0caa219d" width="800" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/70a00861-bb38-4651-b488-13cb660c759c" width="800" />
 


</p>

### 4. Real-Time Management Dashboard & Session Tracking
A live dashboard for clinic owners and doctors, featuring:
* **Active Session Tracking:** Periodic background polling and live UI timers to monitor ongoing patient sessions.
* **Doctor Queue Management:** Real-time patient queue updates, session actual vs. expected duration tracking, and digital medical notes.

### Doctor Queue & Session Management
<p align="center">
  <img src="https://github.com/user-attachments/assets/7fd42cb5-7bd8-438c-8e6f-178278b97bc5" width="800" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/25b6435c-dd54-4a33-a811-2e5ac5e6d9c0" width="800" />
  

</p>

### Owner Live Dashboard (Real-Time Tracking)
<p align="center">
  <img src="https://github.com/user-attachments/assets/2c1fafd2-897f-4a80-8d3a-b09cda42df98" width="800" />

</p>

### Clinic Resource Management (Doctors & Rooms)
<p align="center">
  <img src="https://github.com/user-attachments/assets/2370f89c-9c6e-4b70-b86e-82c02a02558e" width="800" />
  <img src="https://github.com/user-attachments/assets/8739becc-c1e9-420a-839f-fae161df56dc" width="800" />


</p>

---

## Tech Stack
* **Frontend:** Flutter, Dart, Clean Architecture, BLoC/Cubit, GetIt (Dependency Injection), Dio.
* **Backend:** Node.js, Express.js.
* **Database:** PostgreSQL (Complex Relational Schemas).
* **Deployment & Networking:** Docker, Hybrid Local/Cloud infrastructure.
