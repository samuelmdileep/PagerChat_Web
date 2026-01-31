<img width="603" height="1029" alt="Screenshot 2026-01-31 061457" src="https://github.com/user-attachments/assets/82a2ffb3-2907-41c4-84ad-ce4658165dd0" /># 📟 Pager Chat

> **"What if your smartphone was a 90s Pager?"**

**Pager Chat** is a retro-themed real-time messaging application built with **Flutter** and **Firebase**. It combines the nostalgia of 1990s beepers with modern real-time communication technology.

---

## 🚀 Live Demo
**Try it on the Web:** (https://samuelmdileep.github.io/PagerChat_Web/)


---

## ✨ Features

* **📟 Unique Pager ID System:** Forget phone numbers. Add friends using their unique 6-digit Pager ID.
* **⚡ Real-Time Messaging:** Instant message delivery powered by **Cloud Firestore**.
* **🎨 Retro UI:** A fully custom "Dark Mode" aesthetic with terminal-green text and monospace fonts.
* **🔔 Smart Notifications:**
    * Background & Terminated state handling via **Firebase Cloud Messaging (FCM)**.
    * Local heads-up notifications when the app is active.
* **🔐 Secure Authentication:** Email/Password login with a smart "Self-Healing" profile system.
* **📧 Smart Redirects:** Automatically detects and opens the native mail app (Gmail/Apple Mail) for email verification.
* **🌐 Web Optimized:** Custom renderer settings and disabled context menus for a native app feel on the browser.

---

## 📱 Screenshots

| Login Screen | Chat List | Conversation |
|:---:|:---:|:---:|
|  <img width="608" height="1022" alt="Screenshot 2026-01-31 061012" src="https://github.com/user-attachments/assets/6994e6a8-b444-4086-85ae-2e5a9593ee5b" />
img width="611" height="1021" alt="Screenshot 2026-01-31 060906" src="https://github.com/user-attachments/assets/2a6a04eb-7cb7-42b4-8119-24ddb4f26dad" />
| <img width="608" height="1022" alt="Screenshot 2026-01-31 061012" src="https://github.com/user-attachments/assets/d788cbbd-bf10-4b09-ad7d-36c1231641aa" />  |    <img width="603" height="1029" alt="Screenshot 2026-01-31 061457" src="https://github.com/user-attachments/assets/ba4577c4-3b67-4adc-be80-07e45417f890" />   |




---

## 🛠️ Tech Stack

* **Frontend:** [Flutter](https://flutter.dev/) (Dart)
* **Backend:** [Firebase](https://firebase.google.com/)
    * Authentication
    * Cloud Firestore
    * Cloud Messaging (FCM)
* **State Management:** `StreamBuilder` & Native Flutter State
* **Deployment:** GitHub Pages (Web)

---

## ⚙️ Installation & Setup

If you want to run this project locally, follow these steps:

### 1. Clone the Repo
```bash
git clone [https://github.com/](https://github.com/)[YOUR-USERNAME]/PagerChat_Web.git
cd PagerChat_Web
2. Install Dependencies
Bash
flutter pub get
3. Firebase Configuration (Crucial)
This project relies on Firebase. You must provide your own firebase_options.dart.

Create a project in the Firebase Console.

Run flutterfire configure in your terminal.

Select your project and platforms (Android, iOS, Web).

4. Run the App
For Android:

Bash
flutter run
For Web:

Bash
flutter run -d chrome
📦 Download APK
Want to test it on Android? Download the latest release here: Download PagerChat.apk (Add your Google Drive/Dropbox link here)

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📝 License
Distributed under the MIT License. See LICENSE for more information.

Made with 💚 and a lot of ☕ by [Your Name]


### **How to make this look perfect:**
1.  **Screenshots:** Create a folder in your project called `assets/screenshots`. Take 3 screenshots of your app, name them `login.png`, `list.png`, and `chat.png`, and put them there.
2.  **Links:** Replace `[YOUR-USERNAME]` with your actual GitHub username.
3.  **APK Link:** If you uploaded the APK to Drive, paste that link in the "Download
