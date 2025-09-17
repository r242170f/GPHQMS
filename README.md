# Hospital Queue Management System (HQMS) – Gweru Provincial Hospital

## 1. User Authentication & Roles
- **Secure Login System** with username and password.  
- **Role-based access control**:  
  - **Admin**: Full system control (manage users, view/edit reports, configure departments).  
  - **Clerks/Receptionists**: Register patients, assign queue numbers.  
  - **Doctors/Nurses**: View queue, call next patient, mark attendance.  
  - **Pharmacy/Lab Staff**: Manage patient queues for their departments.  
- **Password encryption** for security.  

---

## 2. Patient Registration
- Capture patient details: **name, age, gender, hospital number, department**.  
- Automatically generate a **queue number**.  

---

## 3. Queue Management
- Display **real-time queue status** for each department.  
- Staff can **call next patient** and mark as **attended**.  
- Supports **multiple departments** (e.g., Outpatients, Pharmacy, Laboratory).  

---

## 4. Doctor/Staff Interface
- Show list of **waiting patients**.  
- Options:  
  - **In Consultation**  
  - **Completed**  

---

## 5. Public Display System
- Big screen in waiting hall showing:  
  - Current **patient number** being served.  
  - **Department** and **room number**.  

---

## 6. Administration Panel
- Manage hospital **departments**.  
- Add, remove, or edit **staff user accounts**.  
- **Reset passwords**.  
- Configure **system settings** (e.g., consultation time per patient).  

---

## 7. Reports & Analytics
- Track **daily/weekly/monthly** patient visits.  
- Monitor **average waiting time** per department.  
- Identify **peak hours**.  
- Export reports (**Excel/PDF**).  

---

## 8. Technology Stack
- **Frontend**: React + Tailwind CSS  
- **Backend**: Python (Flask or Django REST Framework)  
- **Database**: MySQL/PostgreSQL (scalable)  
- **Authentication**: JWT (JSON Web Tokens) or Django Auth  

---

## 9. System Objectives
- Ensure **secure and role-based access** to patient data.  
- Reduce **waiting time** and overcrowding.  
- Improve **staff accountability** through clear role separation.  
- Provide management with **data-driven insights** for decision-making.  

---
