📟 Pager Chat

“What if your smartphone worked like a 90s pager?”

Pager Chat is a retro-inspired real-time messaging Flutter Web App built using Flutter and Firebase.
It replaces phone numbers with unique Pager IDs, combining old-school simplicity with modern real-time infrastructure.

The app runs entirely in the browser and is hosted on GitHub Pages.

🚀 Live Demo

🌐 Web App:
https://samuelmdileep.github.io/PagerChat_Web/

✨ Key Features
📟 Pager ID–Based Messaging

Chat using unique Pager IDs instead of phone numbers.

⚡ Real-Time Chat

Instant message synchronization powered by Cloud Firestore.

🎨 Retro Terminal UI

Dark theme, neon-green highlights, boxy containers, minimal distractions.

🔔 Smart Notifications

Firebase Cloud Messaging (background & terminated states)

Local in-app notifications when active

🔐 Secure Authentication

Email / Password login

Auto-repair user profile creation

📧 Smart Email Redirect

Opens native mail apps for verification links

🌐 Web-Optimized

Flutter Web build

Custom web renderer

Disabled context menu for native-app feel

📱 Screenshots

Login • Chat List • Conversation

<p float="left"> <img src="https://github.com/user-attachments/assets/6994e6a8-b444-4086-85ae-2e5a9593ee5b" width="250" /> <img src="https://github.com/user-attachments/assets/2a6a04eb-7cb7-42b4-8119-24ddb4f26dad" width="250" /> <img src="https://github.com/user-attachments/assets/82a2ffb3-2907-41c4-84ad-ce4658165dd0" width="250" /> </p>
🛠️ Tech Stack

Frontend

Flutter (Dart)

Backend

Firebase

Authentication

Cloud Firestore

Cloud Messaging (FCM)

State Handling

Native Flutter state

StreamBuilder

Deployment

GitHub Pages (Web)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/YOUR-USERNAME/PagerChat_Web.git
cd PagerChat_Web

2️⃣ Install Dependencies
flutter pub get

3️⃣ Firebase Configuration (Required)

This project uses Firebase. You must generate your own configuration.

flutterfire configure


Select:

Android

iOS

Web

This will generate firebase_options.dart.

⚠️ Do not commit Firebase credentials publicly.

4️⃣ Run the App

Web

flutter run -d chrome


Android

flutter run

📦 APK Download

📲 Android APK:
(Coming soon – Web version is currently live)

🧪 Current Project Status
✅ Fully Working

Pager ID system

Real-time chat

Contact save / edit / delete

Unknown chat detection

Search by name or Pager ID

Unread indicator (animated pulse)

Firebase authentication & notifications

Web deployment

⚠️ Partially Implemented

Unread logic uses local state (not Firestore)

No unread message count yet

🔮 Planned Improvements

Firestore-based unread tracking

Unread message count badge

Read receipts (seen / delivered)

Typing indicators

Message pagination

Media & file sharing

End-to-end encryption

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a branch

git checkout -b feature/YourFeature


Commit changes

git commit -m "Add YourFeature"


Push and open a Pull Request

📝 License

Licensed under the MIT License.
See LICENSE for details.

Made with 💚 and ☕ by Samuel M Dileep
