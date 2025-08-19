#  🏥 MedCare

MedCare is a **full-stack healthcare management platform** designed to streamline communication between **patients, doctors, and administrators**.  
It allows patients to manage appointments, view their medical history, and connect with doctors — while doctors can track patient records, appointments, and provide medical guidance efficiently.

## 👥 Project Members

| Name                     |
|--------------------------|
| **Shreya Gemad**         |
| **Unnati Mane Deshmukh** |
| **Priyanka Phadatre**    |
| **Mayuri Surve**         |
| **Siddhi Patil**         |


## ✨ Features

### 👨‍⚕️ Patient Module
- Patient Dashboard with personalized health data
- Appointment booking & tracking
- View & download medical history
- Upload & access lab reports
- Profile management with secure login

### 🩺 Doctor Module
- Doctor Dashboard to manage patients
- View patient details & medical history
- Manage appointments & availability
- Generate and share e-prescriptions
- Provide medical recommendations

### 🔄 Common Features
- Secure authentication (JWT/OAuth2)
- Responsive design (Mobile + Desktop)
- REST API-based communication
- Modern UI with Angular
- Notifications via Email/SMS for reminders

## 📂 Project Structure
```
### **Backend (Django REST API)**
medcare_backend/
├── manage.py
├── medcare_backend/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── patients/
│ ├── models.py
│ ├── serializers.py
│ ├── views.py
│ └── urls.py
├── doctors/
│ ├── models.py
│ ├── serializers.py
│ ├── views.py
│ └── urls.py
└── appointments/
├── models.py
├── serializers.py
├── views.py
└── urls.py
```
### **Frontend (Angular)**

---

```
medcare-frontend/
├── src/
│ ├── app/
│ │ ├── components/
│ │ │ ├── patient/
│ │ │ │ ├── patient-dashboard/
│ │ │ │ │ ├── patient-dashboard.component.ts
│ │ │ │ │ ├── patient-dashboard.component.html
│ │ │ │ │ └── patient-dashboard.component.css
│ │ │ │ ├── patient-history/
│ │ │ │ │ ├── patient-history.component.ts
│ │ │ │ │ ├── patient-history.component.html
│ │ │ │ │ └── patient-history.component.css
│ │ │ ├── doctor/
│ │ │ │ ├── doctor-dashboard/
│ │ │ │ │ ├── doctor-dashboard.component.ts
│ │ │ │ │ ├── doctor-dashboard.component.html
│ │ │ │ │ └── doctor-dashboard.component.css
│ │ │ │ ├── patient-detail/
│ │ │ │ │ ├── patient-detail.component.ts
│ │ │ │ │ ├── patient-detail.component.html
│ │ │ │ │ └── patient-detail.component.css
│ │ │ ├── shared/
│ │ │ │ └── navbar/
│ │ │ │ ├── navbar.component.ts
│ │ │ │ ├── navbar.component.html
│ │ │ │ └── navbar.component.css
│ │ ├── services/
│ │ │ ├── patient.service.ts
│ │ │ ├── doctor.service.ts
│ │ │ └── appointment.service.ts
│ │ ├── app-routing.module.ts
│ │ └── app.module.ts


```
---

---


