# Documentation of DoctorG
##### Repos Link
 - [Backend](https://github.com/fThAbhishek-Pandey/DoctorGBackend)
 - [Admin Panel](https://github.com/fThAbhishek-Pandey/Admin-Panal-DoctorG)
 - [Patient](https://github.com/fThAbhishek-Pandey/DoctorG-patient-panel)
 - [youtube: showcase]()

---

# Healthcare Management System

This repository contains the code for a comprehensive **Healthcare Management System**. It features distinct panels for **Users (Patients)**, **Doctors**, and **Admin**, allowing for smooth management of appointments, doctor-patient interactions, and system oversight.

## Features

### 1. User Panel (Patient Interface)
This is the interface for patients to manage their healthcare services, book appointments, and interact with doctors.

**Key Features:**
- **User Registration & Login:**
  - Allows patients to sign up and log in with credentials.
  - Profile creation with personal details.
  
- **Search for Doctors:**
  - Search and filter doctors by specialization.
  - View detailed doctor profiles with qualifications, experience, and patient reviews.

- **Appointment Booking:**
  - View available appointment slots for doctors.
  - Book appointments with preferred date and time for in-person consultations.

- **Appointment Management:**
  - View, reschedule, or cancel upcoming appointments.
  - Receive appointment confirmations via notifications.

- **Payments:**
  - Secure online payment gateway for consultation fees and other services.

### 2. Admin Panel
The admin panel allows system-wide management, including overseeing users, doctors, appointments, and overall system performance.

**Key Features:**
- **Admin Login & Dashboard:**
  - Secure JWT-based login for admins.
  - Dashboard with system statistics such as number of users, appointments, and revenue.

- **User & Doctor Management:**
  - Add and manage doctor profiles.
  - Provide login credentials for doctors.

- **Appointment Oversight:**
  - View and manage all appointments (pending, completed, or canceled).
  - Resolve disputes related to appointments or consultations.

### 3. Doctor Panel
This panel allows doctors to manage their schedules, profile, patient communication, and earnings.

**Key Features:**
- **Doctor Registration & Login:**
  - Doctors register and provide credentials for admin approval.
  - Once approved, doctors can manage their profile and appointments.

- **Profile Management:**
  - Update personal and professional information including qualifications, specialties, and consultation fees.

- **Appointment Management:**
  - View upcoming appointments and manage availability by marking time slots as available or unavailable.
  - Complete or cancel appointments with patients as needed.

- **Earnings & Payouts:**
  - Track consultation fees and request payouts from the system.

- **Patient Communication:**
  - Direct messaging or notifications to patients for follow-ups or appointment updates.

- **Analytics Dashboard:**
  - View metrics on appointment volume, earnings, and patient statistics.

---

### Technologies Used
- Frontend: React (with Vite)
- Backend: Node.js with Express
- Database: Mongodb Atlas
- Authentication: JWT (JSON Web Tokens)
- Payment Gateway: Razorpay
  
### Installation
1. Clone the repository:
 - Backend
   
```bash
   git clone https://github.com/yourusername/healthcare-management-system.git
```
 - User Panel (Patient Interface)
```bash
   git clone https://github.com/yourusername/healthcare-management-system.git
```
- Admin Panel
```bash
   git clone https://github.com/yourusername/healthcare-management-system.git
```
2. Install dependencies:
```bash
   npm install
 ```

3. Set up environment variables (.env) and database configurations using .env-templates

4. Run the application:
```bash
   npm run dev
```

---

Feel free to contribute to the project or raise issues if you encounter any problems!


