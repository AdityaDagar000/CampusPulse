# CampusPulse 🚀
**AI-Driven Peer-to-Peer Resource Mesh for Students**

CampusPulse is a hyperlocal mobile solution that transforms a university campus into a living library. It enables students to share resources—from calculators to textbooks—using AI-powered inventory management and a secure, trust-based handshake protocol.

---

## 🌟 Key Features

- **📸 AI Digital Locker:** Take a photo of any item, and Google Gemini 1.5 Flash automatically identifies, tags, and categorizes it for your inventory.
- **⚡ Flash Requests:** Need something urgently? Send a request that pings nearby students within a 500m radius in real-time.
- **🛡️ Secure PIN Handshake:** A fraud-proof transaction system. Users verify exchanges by swapping a unique 4-digit PIN, securing the peer-to-peer trust loop.
- **💎 Karma Reputation System:** Earn "Karma Points" for every successful trade. Build a profile that reflects your contribution to the campus community.
- **🎓 University SSO:** Restricted access to `@gla.ac.in` domains to ensure a safe, closed-loop environment.

---

## 🛠️ Tech Stack

- **Frontend:** Flutter (Mobile & Web)
- **Backend:** Firebase (Authentication, Firestore, Hosting)
- **AI Intelligence:** Google Gemini 1.5 Flash (Vision & Text processing)
- **Maps:** Google Maps SDK for hyperlocal discovery
- **State Management:** Provider / Riverpod

---

## 🚀 Live Demo & Installation

### **Web MVP**
Check out the live web prototype here:  
🔗 [**[YOUR_FIREBASE_HOSTING_LINK_HERE]**](http://your-app-link.web.app)


---

## 🏗️ Architecture Overview

CampusPulse follows a "Logic-First" architecture to ensure data integrity:

1. **The Upload:** `Flutter` -> `Firebase Storage` -> `Gemini API` -> `Firestore`.
2. **The Request:** `User Request` -> `Geo-query` -> `Push Notification` -> `Nearby Peers`.
3. **The Handshake:** `Transaction Document` -> `PIN Generation` -> `Two-way Verification` -> `Karma Update`.



---
