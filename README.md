#  🏥 MediCare

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
# **🚀 Installation & Setup**

## **📂 Backend (Flask)**

**📂 Step 1: Clone the repository**  
```bash
git clone https://github.com/siddhipatil1593/medcare.git
cd medcare_backend
```
**⚙️Step 2: Create virtual environment**
```
python -m venv venv
venv\Scripts\activate
```
**📦 Step 3: Install dependencies**
```
pip install -r requirements.txt
```
**▶️  Step 4: Start backend server**
```
python app.py
```

## **📂Frontend (Angular)**
```
cd medcare-frontend
```
***Install dependencies**
```
npm install
```
***Run frontend**
```
ng serve -o
```
# **📸 Screenshots**
<img width="1298" height="902" alt="screenshort" src="https://github.com/siddhipatil1593/Medicare/blob/24394cfbee8d811c996e246997dd9b37dca3d07a/Screenshot%20(60).png" />
```
<img width="1298" height="902" alt="screenshorts" src="https://github.com/siddhipatil1593/Medicare/blob/f31072a1baa8369e1d368e3913acdc31b541c4df/Screenshot%20(61).png"/>
```
<img width="1298" height="902" alt="screenshorts" src="https://github.com/siddhipatil1593/Medicare/blob/13e3318b97be058baa16897f094a73f1235ba593/Screenshot%20(62).png"/>
```
<img width="1298" height="902" alt="screenshorts" src=""/>
```
<img width="1298" height="902" alt="screenshorts" src=""/>
```
<img width="1298" height="902" alt="screenshorts" src=""/>
```
<img width="1298" height="902" alt="screenshorts" src=""/>
