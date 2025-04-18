# 💊 EasyPharm - ePharmacy Web Application

EasyPharm is a web-based ePharmacy platform developed as part of a final year project. It provides users with an easy way to browse and purchase medicines, consult doctors, upload prescriptions, manage medical records, and locate nearby pharmacies — all integrated with Firebase services.

## 📌 Features

- 🔐 Firebase Authentication (Login/Logout with Google)
- 💊 Medicine listing with category filtering (e.g., Immunity, Diabetic Care, etc.)
- 🛒 Add to Cart, View Cart, and Checkout
- 📄 Upload and extract text from prescriptions using OCR & ML
- 🧾 Health Record Management (Upload, Preview, Delete)
- 📍 Pharmacy Locator using Google Maps API (based on user's location)
- 📂 Admin panel to manage medicines and doctors
- 📧 Email + SMS confirmation after doctor appointment booking
- 🧾 PDF Invoice generation after payment

## 🧰 Technologies Used

- HTML, CSS, JavaScript (Vanilla)
- Firebase (Auth, Firestore, Storage)
- Google Maps API
- Tesseract.js (OCR)
- jsPDF (Invoice PDF)
- Razorpay (Payment Gateway)

## 🚀 Getting Started

### Prerequisites

- A Firebase project with:
  - Firestore Database
  - Firebase Authentication (Google Sign-In enabled)
  - Firebase Storage
- Google Maps API Key
- Razorpay API Keys

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/easypharm.git
   cd easypharm
