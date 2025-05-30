# 🔐 Authentication App - Flutter + Spring Boot Fullstack

A responsive full-stack Login and Register application built using Flutter (frontend) and Spring Boot (backend) with MySQL as the database. This app allows user registration, login, and redirects to a home page after authentication. Backend APIs are RESTful and frontend is styled using Bootstrap.

## 📁 Folder Structure
authentication-app/
├── frontend/           # Flutter app
└── backend/            # Spring Boot project

## ⚙️ Prerequisites

### Backend:
- Java 17 or above
- Spring Boot
- Maven
- MySQL (any version)
- Postman (optional, for testing APIs)

### Frontend:
- Flutter SDK (3.x recommended)
- Dart
- Android Studio or VS Code with Flutter plugin
- Android Emulator or Physical Device


## 📦 How to Download and Set Up

1. Download ZIP
   - Click on Code → Download ZIP.

2. Unzip File
   - Extract the downloaded ZIP file to your preferred location.


## 🚀 Backend Setup (Spring Boot + MySQL)

1. Open the backend folder:
  cd authentication-app/backend

2. Import into IntelliJ or VS Code (or any IDE that supports Spring Boot).

3. ✅ Configure application.properties:

spring.datasource.url=jdbc\:mysql://localhost:3306/authentication\_db
spring.datasource.username=your\_mysql\_username
spring.datasource.password=your\_mysql\_password


4. SetUp MySQL database Schema to directly contact with entity.

5. Run the backend in terminal of your editor.

6. Test API using Postman:

   * POST → http://localhost:8080/api/auth/register
   * POST → http://localhost:8080/api/auth/login

## 📱 Frontend Setup (Flutter)

1. Open the frontend folder:

   terminal :
     cd authentication-app/frontend


2. Install dependencies:

   terminal :
     flutter pub get

3. Run the app:

   terminal :
     flutter run


5. 💡 Make sure backend is running and Android Emulator or physical device is connected.

## 🧪 Features

* ✅ Register new users
* ✅ Secure login
* ✅ Redirect to home screen
* ✅ Form validation for inputs
* ✅ Responsive design with Bootstrap
* ✅ API error handling
* ✅ Full backend integration with Spring Boot

## 📷 Video Reference Link for Output :

Link : https://www.linkedin.com/posts/vasanth-s-5a1556246_flutter-springboot-fullstackdeveloper-activity-7334227317663088642-LpGv?utm_source=share&utm_medium=member_desktop&rcm=ACoAADzzHMkB-2MlUiKPrvwFEKq-BdpG_4LM0is

## 📌 Notes

* Change the backend URL in Flutter code (`http://10.0.2.2:8080/` for Android emulator).
* For real device or deployment, replace with appropriate local IP or domain.

## ✉️ Contact

For queries, reach out to:

* **Name:** Vasanth S
* **Email:** mailto:vasanthvnr31@gmail.com
* **GitHub:** vasanthvnr
