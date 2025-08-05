# Health & Nutrition App

This Android-based Health and Nutrition app is designed to connect patients with certified nutritionists, enabling professional diet guidance and real-time communication. Developed using Java and XML in Android Studio, it incorporates local data storage using SQLite and custom database handling through a DBHelper class.

---

## 📱 Project Description

The Health & Nutrition App provides a simple and secure platform for patients to interact with nutritionists. Patients can register and log in to ask diet-related questions, while nutritionists respond with appropriate guidance. Nutritionists must upload valid certificates during signup, which are reviewed and approved by an admin before they can access the system.

The app stores user data, queries, and responses locally using a custom-built SQLite database, ensuring smooth offline access and efficient data handling. Firebase Cloud Messaging (or a similar mechanism) may be used for real-time updates if extended in the future.

---

## 👥 User Roles

### 🧑‍⚕️ Nutritionists
- Register with personal details and upload a valid certificate
- Await admin approval before accessing the system
- Respond to patient queries once verified

### 🧑 Patients
- Register/login securely
- Submit health or diet-related queries
- View responses from verified nutritionists

### 👤 Admin
- Verifies nutritionist certificates
- Approves or rejects new nutritionist accounts

---

## 🧰 Tech Stack

- **Language:** Java  
- **UI:** XML (Android Layouts)  
- **Database:** SQLite with custom **DBHelper** class  
- **IDE:** Android Studio  
- **Architecture:** Modular, with clear separation of concerns between activities and data operations

---

## 📂 Local Storage Structure

The app uses SQLite via a custom `DBHelper` class to store:

- User login and registration data  
- Nutritionist certificate metadata  
- Patient queries and nutritionist replies  
- Admin-verified account statuses

---

## 🎯 Purpose

The primary goal of this app is to facilitate a trusted and accessible communication channel between patients and professional nutritionists, particularly for those who may not have easy access to in-person consultations. The system ensures that only verified professionals can offer advice, enhancing safety and credibility.

---

> Built for providing trusted nutritional support — anytime, anywhere.
