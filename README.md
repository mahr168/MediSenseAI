# MediSense AI 🩺
### Your Smart Health Companion

MediSense AI is a professional Android healthcare application that puts 
medical intelligence in the palm of your hand. Built with Java 21 and 
Material Design, it combines AI-driven symptom analysis, real-time hospital 
discovery, and daily wellness guidance into one seamless experience.

## 🌟 Why MediSense AI?

In many regions, access to quick medical guidance is limited. MediSense AI 
bridges that gap by providing instant, AI-powered health insights — helping 
users understand their symptoms, find nearby care, and make informed 
decisions before or instead of a clinic visit.

## 🚀 Core Features

### 🩺 AI Disease Prediction
Select from 48 symptoms across 8 body systems — General, Neurological, 
Respiratory, Cardiovascular, Digestive, Musculoskeletal, Skin, and Urinary. 
The built-in scoring engine matches your symptoms against 23 conditions 
including Flu, COVID-19, Dengue, Typhoid, Malaria, Hepatitis, Cardiac 
Emergency, UTI, Diabetes, and more. Every result includes a confidence 
score, urgency level (Low / Medium / High / Emergency), matched symptom 
breakdown, and a detailed recommended action.

### 🗺️ Nearby Hospitals & Clinics
Uses GPS and the free OpenStreetMap Overpass API (no API key required) to 
find hospitals, clinics, pharmacies, and health centres within 5 km. Filter 
by type, get turn-by-turn directions via Google Maps, call directly from 
the app, and open a full map view — all in one screen.

### 🚨 Emergency Services
A dedicated emergency screen with one-tap calling to Rescue 1122. Designed 
with a dark urgent UI, pulsing animation, and clear instructions to keep 
the user calm in a crisis.

### 💡 Daily Health Tips
22 expert-backed health tips across 6 categories — Nutrition, Exercise, 
Sleep, Mental Health, Preventive Care, and Hygiene. Features a rotating 
"Tip of the Day" based on the calendar date, with category filters and 
detailed evidence-based explanations for each tip.

### 🔐 Secure Authentication
Full sign-up and sign-in flow with a 3-step forgot password system using 
security questions. Passwords are stored securely per-user. Includes 
registration with a custom security question for account recovery.

### 👤 User Profile
Manage your display name, change your password, toggle dark mode and 
notifications, view your prediction history count, and delete your account 
— all from a clean, card-based profile screen.

## 🛠️ Tech Stack

- **Language:** Java 21
- **Platform:** Android (Min SDK 21 / Android 5.0+)
- **UI:** Material Design 3, CardView, ConstraintLayout
- **Location:** Google Play Services FusedLocationProvider
- **Maps Data:** OpenStreetMap via Overpass API (free, no key)
- **Storage:** SharedPreferences
- **Architecture:** Single-activity screens with Intent navigation

## 📱 Screens

Splash → Login / Register → Dashboard → Prediction / Nearby / Emergency 
/ Health Tips / Profile → Forgot Password

## ⚠️ Disclaimer

MediSense AI is for informational purposes only and does not constitute 
medical advice, diagnosis, or treatment. Always consult a qualified 
healthcare professional for any medical concerns.
