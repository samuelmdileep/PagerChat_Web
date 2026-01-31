# 📟 Pager Chat

<p align="center">
  <img src="https://github.com/user-attachments/assets/6994e6a8-b444-4086-85ae-2e5a9593ee5b" width="300" alt="Pager Chat Logo">
  <br>
  <b>"What if your smartphone worked like a 90s pager?"</b>
  <br>
  <i>A retro-inspired, real-time messaging Flutter Web App.</i>
</p>

---

## 🌐 Overview

**Pager Chat** bridges the gap between 90s nostalgia and modern cloud infrastructure. By replacing intrusive phone numbers with unique **Pager IDs**, it offers a lightweight, lo-fi terminal experience built for the modern web.

[**🚀 Launch Live Demo**](https://samuelmdileep.github.io/PagerChat_Web/) | [**📦 Download APK** (Coming Soon)](#)

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| **📟 Pager ID System** | Chat using unique alphanumeric IDs instead of private phone numbers. |
| **⚡ Real-Time Sync** | Instant message delivery powered by **Firebase Cloud Firestore**. |
| **🎨 Retro UI** | Terminal-style dark theme with neon-green highlights and boxy containers. |
| **🔔 Smart Alerts** | Background notifications via **FCM** and custom in-app local alerts. |
| **🌐 Web Optimized** | Custom renderers and disabled context menus for a native-app feel. |

---

## 📱 Interface Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/6994e6a8-b444-4086-85ae-2e5a9593ee5b" width="250" alt="Login Screen" />
  <img src="https://github.com/user-attachments/assets/2a6a04eb-7cb7-42b4-8119-24ddb4f26dad" width="250" alt="Chat List" />
  <img src="https://github.com/user-attachments/assets/82a2ffb3-2907-41c4-84ad-ce4658165dd0" width="250" alt="Conversation" />
</p>

---

## 🛠️ Technical Architecture

### **The Stack**
* **Frontend:** [Flutter](https://flutter.dev) (Dart)
* **Database:** Cloud Firestore (NoSQL)
* **Auth:** Firebase Authentication
* **Messaging:** Firebase Cloud Messaging (FCM)
* **Deployment:** GitHub Pages

---

## ⚙️ Setup & Installation

### 1️⃣ Clone & Install
```bash
git clone [https://github.com/samuelmdileep/PagerChat_Web.git](https://github.com/samuelmdileep/PagerChat_Web.git)
cd PagerChat_Web
flutter pub get
2️⃣ Firebase Linkage
This project requires a Firebase instance. Initialize your own config using:

Bash
flutterfire configure
Select Web, Android, and iOS to generate firebase_options.dart.

3️⃣ Execution
Bash
# Run on Web
flutter run -d chrome

# Run on Mobile
flutter run
🔮 Roadmap
[x] Phase 1: Core Pager ID routing & Real-time chat.

[x] Phase 2: Contact management & Search.

[ ] Phase 3: Server-side unread tracking (Firestore integration).

[ ] Phase 4: Typing indicators & Message pagination.

[ ] Phase 5: End-to-end encryption (E2EE).

🤝 Contributing
Contributions are what make the open-source community such an amazing place!

Fork the Project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your Changes (git commit -m 'Add AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📝 License
Distributed under the MIT License. See LICENSE for more information.

<p align="center"> Made with 💚 and ☕ by <b>Samuel M Dileep</b> </p>


Would you like me to help you create a **GitHub Action** to automate your deployment
