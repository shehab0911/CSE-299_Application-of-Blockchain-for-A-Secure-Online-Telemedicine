#  Blockchain in Secure Online Telemedicine System
Developer --- Rofiqul Alam Shehab
---
## screenshots
### Homepage
![homepage snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/homepage.png)
### Patient Registration
![registration page snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/patient_registration.png)
### Patient Login
![patient login](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/patient_login.png)
### Patient Dashboard
![patient dashboard snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/patient_dashboard.png)
### Patient Payment
![patient payment invoice snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/invoice.png)
### Doctor Dashboard
![doctor dashboard snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/admin_doctor.png)
### Admin Dashboard
![admin dashboard snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/admin_dashboard.png)
### Doctor Generates Prescription 
![doctor prescription snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/doctor_generate_prescription.png)
### Patient Downloads Description
![patient prescription snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/prescription.png)
### Doctor & Patient Make Video Call & Chatting
![doctor snap](https://github.com/zaynnissan/Application-of-Blockchain-for-a-secure-online-telemedicine/blob/master/static/screenshots/video_calling.png)

---
# THE WEBSITE HAS BEEN DEVELOPED WITH THE HELP OF FUNCTIONS.

# ADMIN

1) Create an account for them. Then sign in (No approval Required).
2) Ability to register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
3) Able to admit/view/approve/reject/discharge a patient (discharge patient when treatment is done).
4) Ability to generate/download invoices in pdf format (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
5) Appointment viewing/booking/approval (approve those appointments which is requested by patient).

# DOCTOR

1) Fill out an application for a position at a hospital. Then Sign in.
2) Only the patient details allocated to that doctor by admin can be viewed.
3) Can see a list of their discharged patients.
4) Can access their admin-booked appointments.
5) When the doctor attends their appointment, they have the option to remove it.

# PATIENT

1) Create an account for a hospital admission. Then sign in (Approval required by hospital admin, Then only patient can login).
2) Access to allocated doctor's information, such as ( specialization, mobile, address).
3) Can check the status of their scheduled appointment (pending/confirmed by admin).
4) Appointments can be scheduled (Admin permission is necessary).
5) Ability to view/download invoice pdf (Only when that patient is discharged by admin).

---

# HOW TO RUN THIS PROJECT

- Download and install Python (3.7.6) (When installing Python, don't forget to tick the Add to Path box.)
- Run the following commands on a terminal:
"' pip install django==3.0.5 pip install django-widget-tweaks django-widget-tweaks django-widget-tweaks django-widget-tweaks
"'pip install xhtml2pdf"' - Download and Extract This Project Zip Folder
- In Terminal, go to the project folder. Then execute the commands below:
makemigrations.py "' py manage.py
migrate.py py manage.py
py manage.py runserver "' - Now type the following URL into your computer's browser.
```
http://127.0.0.1:8000/
```


