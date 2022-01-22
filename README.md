# Secure Online Telemedicine System
Developer - \Rofiqul Alam Shehab
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
## Functions
### Admin
- Signup their account. Then Login (No approval Required).
- Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
- Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).
- Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
- Can view/book/approve Appointment (approve those appointments which is requested by patient).

### Doctor
- Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).
- Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.
- Can view their discharged(by admin) patient list.
- Can view their Appointments, booked by admin.
- Can delete their Appointment, when doctor attended their appointment.

# Patient
1) Create an account for a hospital admission. Then sign in (Approval required by hospital admin, Then only patient can login).
2) Access to allocated doctor's information, such as ( specialization, mobile, address).
3) Can check the status of their scheduled appointment (pending/confirmed by admin).

4) Appointments can be scheduled (Admin permission is necessary).

5) Ability to view/download invoice pdf (Only when that patient is discharged by admin).

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps
```
## Drawbacks/LoopHoles
- Any one can be Admin. There is no Approval required for admin account. So you can disable admin signup process and use any logic like creating superuser.
- There should be at least one doctor in hospital before admitting patient. So first add doctor.
- On update page of doctor/patient you must have to update password.


# SimpleWebRTC Sample Talky App

To get started, you will first need to edit `public/index.html` to set your API key.

See the section marked `IMPORTANT SETUP`, and change the placeholder `YOUR_API_KEY` to be the API key you were provided. API KEY '492c9fa0a4b959099ceb1959'

You can retrieve your API key by visiting [https://accounts.simplewebrtc.com](https://accounts.simplewebrtc.com).

## Running

1. `npm install`
2. Edit `public/index.html` as described above.
3. `npm start`
4. Go to [https://localhost:8080/](https://localhost:8080)


## Deploying to Static/Shared Hosting

1. `npm install`
2. Edit `public/index.html` as described above.
3. `npm run build`
4. Copy the contents of the `./dist` folder to your hosting location.
5. Ensure your hosting location is served via HTTPS.


## Sound Configuration

Sound effects for peers joining/leaving, messages, and sound output testing can be configured.

Put your audio files into the `/public` directory, and uncomment the desired `<meta />` tags in `/public/index.html`, setting the `content` attribute to the URL of the audio file:

```html
<meta name="simplewebrtc-sound-message-receive" content="/url-of-mp3-file" />
<meta name="simplewebrtc-sound-message-send" content="/url-of-mp3-file" />
<meta name="simplewebrtc-sound-peer-enter" content="/url-of-mp3-file" />
<meta name="simplewebrtc-sound-peer-exit" content="/url-of-mp3-file" />
<meta name="simplewebrtc-sound-test-output" content="/url-of-mp3-file" />
```

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Facebook](https://fb.com/)
- [Subscribe my Channel On Youtube](https://youtube.com/)
