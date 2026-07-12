# Swasthya Card (ABHA) Integration Portal

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()

An open-source digital health platform designed to seamlessly integrate with India's **Ayushman Bharat Digital Mission (ABDM)** ecosystem. This application allows users to create, link, and manage their **Swasthya Card (ABHA - Ayushman Bharat Health Account)**, transforming how they store and share medical records.

---

## 🚀 Key Features

* **Instant ABHA Creation:** Create a 14-digit Swasthya Card instantly using Aadhaar or Mobile number via secure OTP verification.
* **Digital Health Locker:** Securely store, aggregate, and view medical history, including doctor prescriptions, diagnostic reports, and discharge summaries.
* **Consent-Based Sharing:** Share medical records with verified healthcare professionals seamlessly using ABDM’s strict data-privacy consent framework.
* **Unified Health Interface (UHI):** Book appointments, discover lab services, and interact with teleconsultation services.
* **Paperless QR Check-ins:** Scan QR codes at empanelled hospitals for instant, hassle-free registration, cutting down long waiting lines.

---

## 🛠️ Tech Stack

* **Frontend:** React.js / React Native (Mobile)
* **Backend:** Node.js (Express) / Python (FastAPI)
* **Database:** PostgreSQL / MongoDB (fully encrypted at rest)
* **APIs:** National Health Authority (NHA) Sandbox APIs / ABDM M1, M2, M3 Milestones

---

## ⚙️ Getting Started

### Prerequisites
Before running the project, ensure you have:
* Node.js (v18.x or higher) or Python (3.10+ )
* Access to the [ABDM Sandbox Credentials](https://sandbox.abdm.gov.in/) (Client ID and Client Secret)

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/swasthya-card-portal.git](https://github.com/your-username/swasthya-card-portal.git)
   cd swasthya-card-portal
