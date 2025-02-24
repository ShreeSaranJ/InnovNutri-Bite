# 🍽️ InnovNutri-Bite

**AI-powered Nutrition Assistant** that provides personalized meal plans and real-time grocery price tracking to help users make budget-friendly and healthy dietary choices.

## 🌟 Features

✅ **AI Chatbot** – Provides personalized nutrition advice based on user input (age, diet type, weight, height, affordability, etc.).

✅ **Smart Meal Planner** – Generates balanced meal plans considering real-time grocery prices.

✅ **Google Authentication** – Ensures a personalized experience and saves user data securely.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Firebase (Firestore, Authentication)
- **AI Models:** Gemini-based chatbot
- **APIs & Data:** Custom meal planner API
- **Additional Tools:** Streamlit (for AI-based meal suggestions)

---

## 🔥 About Firebase

Firebase is used for authentication and database management in **InnovNutri-Bite**:

- **Firestore Database**: Stores user preferences, meal plans, and chatbot interactions.
- **Authentication**: Google Sign-In enables personalized user experiences.
- **Hosting (Optional)**: Can be used to deploy the web app.

To set up Firebase:
1. Create a project in [Firebase Console](https://console.firebase.google.com/).
2. Enable Firestore and Authentication.
3. Get the Firebase config keys and add them to your `.env` file.

---

## 🚀 Installation Guide

### **1️⃣ Clone the Repository**
```sh
 git clone https://github.com/MSachin11/innovnutri-bite.git
 cd innovnutri-bite
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Setup Environment Variables**
Create a `.env` file in the project root and add your API keys:
```sh
REACT_APP_GEMINI_API_KEY=your_gemini_api_key
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_GROCERY_API=your_grocery_api_key
```
👉 **Note:** Replace `your_api_key` with actual API keys from respective providers.

### **4️⃣ Start the Development Server**
```sh
npm start
```
Now, open [http://localhost:3000](http://localhost:3000) to view the app in the browser.

---

## 🔑 Getting API Keys

| API Service     | Get Your Key Here |
|----------------|----------------|
| **Google Firebase** | [Firebase Console](https://console.firebase.google.com/) |
| **Gemini AI (Chatbot API)** | [Google AI](https://ai.google.dev/) |

---

## ⚡ Setting Up Streamlit

Streamlit is used for AI-based meal planning. Follow these steps to install and run it:

### **1️⃣ Install Streamlit**
```sh
pip install streamlit
```

### **2️⃣ Verify Installation**
```sh
streamlit --version
```

### **3️⃣ Run a Sample App**
```sh
streamlit hello
```
This will launch a demo in your browser.

### **4️⃣ Run the Custom Streamlit App**
```sh
streamlit run app.py
```
Replace `app.py` with your script name if different.

---

## 🏗️ Deployment

For deploying on **Vercel, Netlify, or Firebase Hosting**, set environment variables in their respective settings and build the project:
```sh
npm run build
```

---

## 🤝 Contributing

Want to improve **InnovNutri-Bite**? Follow these steps:
1. **Fork** the repo
2. **Create a branch** (`git checkout -b feature-name`)
3. **Commit changes** (`git commit -m "Added new feature"`)
4. **Push to GitHub** (`git push origin feature-name`)
5. Open a **Pull Request** 🚀

---

## 📜 License

This project is licensed under the **MIT License** – you can freely use and modify it. 😊

---

### 📧 Need Help?
If you have any questions or suggestions, feel free to reach out! 🚀

