# 💚 CareMitra — *Your Digital Health Companion*

**CareMitra** is a comprehensive, disease-responsive web platform built to empower patients facing chronic and critical health challenges such as **cancer**, **diabetes**, **kidney disorders**, and **cardiovascular diseases**.

Our mission is to bridge the gap between medical care and accessibility, especially for **elderly** individuals and those from **rural backgrounds**. By providing tailored health support, timely alerts, and emotional upliftment, CareMitra ensures that care is not just reactive — it’s *proactive*.

---

## 🌟 Core Features

### 🩺 Personalized Healthcare Support
- **Smart Scheme Discovery**: Identifies government or NGO schemes based on illness, disease stage, and employment status.
- **Automated Treatment Tracker**: Sends reminders for chemo, insulin, dialysis, or medication schedules.
- **Tailored Diet Plans**: Recommends dietary plans specific to medical conditions like diabetes, kidney disease, or heart issues.

### 💬 Emotional and Mental Well-being
- **Survivor Stories**: Real stories of recovery tailored to specific health conditions.
- **Weekly Mental Boosts**: Motivational alerts and mindfulness tips to uplift users emotionally.

### 🚨 Emergency Preparedness
- **SOS Alert System**: One-tap SOS sends **live location + medical profile** to caregivers and hospitals.
- **Quick Activation**: Trigger alerts via **lock screen widget** or **voice command**, even in low-mobility scenarios.

---

## 🧰 Tech Stack

| Layer         | Tools / Technologies                                   |
|---------------|--------------------------------------------------------|
| **Frontend**  | React.js, Tailwind CSS                                 |
| **Backend**   | Node.js, Firebase Authentication, Firestore (NoSQL DB)|
| **APIs**      | Google Maps, Edamam, Vonage, OpenTelemetry, Web Push  |
| **Testing**   | Playwright                                             |
| **Deployment**| Vercel                                                 |

---

## 🔑 API Integration Breakdown

CareMitra utilizes **9 APIs**, categorized by difficulty level:

### ✅ Easy (2 pts each)

| API              | Purpose                                                   |
|------------------|-----------------------------------------------------------|
| Web Push API     | Sends daily reminders for medicine, diet, and wellness    |
| RSS Feed API     | Fetches recovery and inspirational stories                |
| JWT Auth Token   | Secure login and session management                       |

### 🟡 Medium (4 pts each)

| API                     | Purpose                                                  |
|-------------------------|----------------------------------------------------------|
| Google Maps Embed API   | Locates nearby hospitals, clinics, and pharmacies        |
| Edamam / Spoonacular API| Provides disease-specific diet plans                     |
| Vonage SMS API          | Sends SOS messages with location and patient data        |

### 🔴 Hard (6 pts each)

| API                    | Purpose                                                    |
|------------------------|------------------------------------------------------------|
| Node Addon API         | Enables hardware-based SOS triggers (e.g., power button)   |
| OpenTelemetry API      | Enables backend monitoring and user flow tracing           |
| Playwright Test API    | Automates testing of user journeys and features            |

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/team-caremitra/caremitra-app.git
cd caremitra-app

#frontend
cd my-app
npm install 

npm run dev

#backend
cd backend
npm install

node app.js

