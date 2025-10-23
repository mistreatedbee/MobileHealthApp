````markdown
# 🏥 Mobile Health App  
**Final Year Project**

> ⚠️ **IMPORTANT:** Always start and keep the **backend server running** before launching this main app project!

---

## 💡 Overview

**Mobile Health** is a **cross-platform healthcare management system** built with **React Native (Expo SDK 54)**.  
It empowers patients, healthcare workers, and administrators to manage appointments, prescriptions, and health records seamlessly.

Designed with a **clean black-and-white minimalist interface**, the app ensures a professional, user-friendly experience while maintaining accessibility and performance.

---

## ✨ Core Features

### 👤 User Management
- Secure **User Authentication** (Login, Signup)
- **Role-based access** — Patient, Worker, and Admin dashboards
- “**Continue as Guest**” mode for limited preview access

### 🩺 Healthcare Functions
- **Book Appointments** with doctors or healthcare workers  
- **View & Cancel Appointments**
- **Workers** can issue and manage **prescriptions**
- **Admins** manage users and roles directly

### 💅 Design & Experience
- Elegant **black-and-white minimalist UI**
- Adaptive for Android, iOS, and Web
- Clear validation, alerts, and clean typography (Serif professional theme)
- Responsive layout across all devices

### 🔥 Technical Highlights
- Built with **React Native (Expo 54)** and **TypeScript**
- Uses **Firebase** and **Node.js/Express backend**
- Modular architecture for easy feature expansion
- Future-ready for offline sync and advanced analytics

---

## ⚙️ Installation & Setup

### 🧩 Prerequisites
- [Node.js (LTS)](https://nodejs.org/)
- [Expo CLI](https://docs.expo.dev/workflow/expo-cli/)  
  ```bash
  npm install -g expo-cli
````

* [Git](https://git-scm.com/)
* (Optional) Android Studio or Xcode for emulator testing

---

### 🚀 Setup Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/mistreatedbee/mobile-health-app.git
   cd mobile-health
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the backend server**
   (Navigate to your backend folder and run:)

   ```bash
   npm start
   ```

   > The backend must be running before launching the mobile app.

4. **Run the app**

   ```bash
   npx expo start
   ```

   * Press **`a`** to launch Android emulator
   * Press **`i`** to launch iOS simulator
   * Or scan the **QR code** using the **Expo Go** app on your phone

---

## 🧠 Tech Stack

| Area            | Technology                                      |
| --------------- | ----------------------------------------------- |
| Framework       | [React Native (Expo SDK 54)](https://expo.dev/) |
| Language        | TypeScript                                      |
| Backend         | Node.js + Express                               |
| Authentication  | Firebase                                        |
| Database        | Firestore                                       |
| Navigation      | React Navigation v7                             |
| Styling         | Custom StyleSheet + Tailwind (optional)         |
| Version Control | Git + GitHub                                    |
| Testing         | Expo Go + Android Emulator                      |

---

## 🧰 Troubleshooting & Common Issues

| Issue                                         | Possible Fix                                                                              |
| --------------------------------------------- | ----------------------------------------------------------------------------------------- |
| **BVLinearGradient not found**                | Install missing dependency: `npx expo install expo-linear-gradient`                       |
| **Version mismatches (expo doctor warnings)** | Run: `npx expo install --fix` or update specific packages                                 |
| **Metro bundler cache issues**                | Run: `npx expo start -c`                                                                  |
| **npm ERESOLVE dependency conflict**          | Run: `npm install --legacy-peer-deps`                                                     |
| **App fails to fetch data**                   | Make sure your backend server is running and reachable (update IP in `_api.ts` if needed) |
| **Cannot connect from emulator**              | Use `http://10.0.2.2:<PORT>` for Android or your local IP for physical devices            |

---

## 📱 Design Overview

| Screen                  | Description                                          |
| ----------------------- | ---------------------------------------------------- |
| **Login**               | Authenticate user or continue as guest               |
| **Signup**              | Register new patients with name, email, and password |
| **Dashboard (Patient)** | View, book, or cancel appointments                   |
| **Dashboard (Worker)**  | View patient list and issue prescriptions            |
| **Dashboard (Admin)**   | Manage users and roles                               |
| **Forgot Password**     | Request a password reset link                        |

---

## 👩‍⚕️ Roles & Permissions

| Role                  | Access                                      |
| --------------------- | ------------------------------------------- |
| **Patient**           | Book appointments, view prescriptions       |
| **Healthcare Worker** | View assigned patients, issue prescriptions |
| **Admin**             | Manage users and assign roles               |

---

## 🧑‍💻 Developers

| Role           | Name          | Responsibilities                          |
| -------------- | ------------- | ----------------------------------------- |
| Project Owner  | **Ashley**    | App architecture, backend integration     |
| Lead Developer | **Mash Dash** | React Native development & Firebase setup |
| UI/UX Designer | **TBA**       | Interface design & visual consistency     |

---

## 🚧 Future Enhancements

### 💬 Communication

* Real-time chat between patients & doctors (using Firebase Realtime DB or Socket.IO)
* Push notifications for appointments, prescription updates, and reminders

### 🏥 Health Services Expansion

* AI-powered symptom checker
* Integration with wearable health devices (Fitbit, Apple Health)
* Electronic Medical Records (EMR) dashboard

### 🛍️ Extended Ecosystem

* **Pharmacy & Delivery System** for medicine orders
* **Ambulance Booking System** integrated with local hospitals
* **Lab Test Scheduling** and result tracking
* **Health Insurance Claim Portal**

### 🎨 UI Enhancements

* Dark mode support
* Multi-language support
* Accessibility compliance (text-to-speech, larger text mode)

---

## 🧩 Commands Reference

| Task                     | Command                             |
| ------------------------ | ----------------------------------- |
| Run development server   | `npx expo start`                    |
| Clear cache              | `npx expo start -c`                 |
| Run backend server       | `npm start` (inside backend folder) |
| Fix dependencies         | `npm install --legacy-peer-deps`    |
| Update Expo SDK packages | `npx expo install --fix`            |
| Run diagnostics          | `npx expo doctor`                   |
| Check outdated packages  | `npm outdated`                      |

---

## 📜 License

Licensed under the **MIT License** — see [LICENSE](LICENSE) for more information.

---

## 💬 Contact

📧 **Email:** [ashleymash013@gmail.com](mailto:ashleymash013@gmail.com)
🐙 **GitHub:** [github.com/mistreatedbee](https://github.com/mistreatedbee)

---

### 🩺 *"Empowering healthcare through technology — connecting patients, providers, and innovation."*

```

---

Would you like me to include a **“Backend Setup Section”** inside this same README (with MongoDB, API routes, and environment setup instructions)?  
It’ll make it one unified guide so anyone can clone and run both backend + frontend together smoothly.
```
