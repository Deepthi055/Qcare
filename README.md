# Hospital Queue Management System

A modern, responsive hospital management system built with React and Firebase.

## Architecture

- High-level system architecture diagram: `ARCHITECTURE.md`
- Editable Draw.io diagram: `architecture.drawio`

## Features

- 🏥 **Professional Landing Page**: Clean, medical-themed design
- 👥 **Patient Portal**: Secure login for patients
- 🔐 **Firebase Authentication**: Secure user management
- 📱 **Responsive Design**: Works on desktop and mobile
- ♿ **Accessibility**: WCAG compliant design

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript, React.js  
- **Backend:** Firebase (Realtime Database & Authentication)  
- **Notifications:** Twilio / SMS API integration  


---

## 📸 Screenshots
<img width="1888" height="929" alt="image" src="https://github.com/user-attachments/assets/e8b3befa-8cee-4a7c-b2ec-7f30460c625b" />
<img width="581" height="862" alt="image" src="https://github.com/user-attachments/assets/adacc1e1-ca39-499f-ac13-1035e2d773f1" />

 

---

## 🚀 Installation

### 1. Clone the repository:  
```bash
git clone https://github.com/Priyadarshinimulloli/Qcare.git

```

### 2. Install dependencies
```bash
npm install
```

### 3. Environment Configuration
1. Copy the example environment file:
   ```bash
   cp .env.example .env
   ```

2. Update `.env` with your Firebase configuration:
   ```env
   VITE_FIREBASE_API_KEY=your_api_key_here
   VITE_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_project_id.firebasestorage.app
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_app_id
   ```

### 4. Firebase Setup
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Authentication with Email/Password
3. Copy your Firebase config to the `.env` file

### 5. Run the development server
```bash
npm run dev
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
## 🔒 Security Notes

- Never commit your `.env` file containing Firebase or API keys.  
- Ensure `.env` is included in `.gitignore`.  
- Configure Firebase database rules to allow only authenticated users to read/write.  
- Do not expose sensitive credentials in screenshots, code snippets, or public repos.

## ⭐ Support

If you find Qcare useful, **give it a star ⭐** and share it with others!

