# 📱 Google Contacts Integration App ✨

Welcome to the **Google Contacts Integration App**! 🚀  
This Spring Boot application allows users to seamlessly view, add, update, and delete their Google Contacts using OAuth2 authentication. 💖  

## 🌟 Features
- 🔍 Fetch and display Google Contacts  
- ➕ Add new contacts  
- ✏️ Update existing contacts  
- ❌ Delete contacts  
- 📸 Supports contact photos! (Yay for cute profile pics!)  
- 🔐 Secure OAuth2 authentication with Google  

## 🛠️ Tech Stack
- **Backend:** Spring Boot (Java 17), Google People API  
- **Frontend:** React (or any preferred frontend framework)  
- **Authentication:** OAuth2 with Google Login  

## 🚀 Getting Started

### 1️⃣ Prerequisites
Make sure you have:  
- Java 17+ installed ☕  
- A Google Cloud project with the People API enabled 🔑  
- OAuth2 credentials set up in `application.properties`  

### 2️⃣ Clone & Run
``` bash
git clone https://github.com/Google-Contacts-API-Springboot/google-contacts-app.git
cd google-contacts-app
mvn spring-boot:run
``` 

### 3️⃣ Set Up OAuth2 Credentials
Update your application.properties:
properties
Copy
Edit
```
spring.security.oauth2.client.registration.google.client-id=YOUR_CLIENT_ID
spring.security.oauth2.client.registration.google.client-secret=YOUR_CLIENT_SECRET
```

### 🎨 How It Works
- Log in with Google ✅
- View and manage your contacts 📇
- Enjoy seamless contact management! 🥰
- 🐛 Issues & Contributions
Found a bug? 🐞 Feel free to open an issue!
Want to contribute? Fork, create a branch, and submit a PR! 🎉
❤️ Thank You!
