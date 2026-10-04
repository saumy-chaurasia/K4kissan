# 🌾 K4kissan — AI-Powered Smart Agricultural Marketplace

> **Khet se Bazaar tak** — Connecting farmers directly with bulk buyers to eliminate intermediaries, lower costs, and establish fair pricing.

![JavaScript](https://img.shields.io/badge/JavaScript-81%25-yellow)
![Framework](https://img.shields.io/badge/Frontend-React%20%7C%20Flutter-blue)
![Backend](https://img.shields.io/badge/Backend-Node.js%20%7C%20Express-green)
![Database](https://img.shields.io/badge/Database-MongoDB%20%7C%20Redis-red)

---

## 📌 Problem Statement

Traditional agricultural supply chains rely heavily on multiple intermediaries, leading to:
- **Low Farmer Revenue:** Middlemen take significant cuts of final crop values.
- **High Buyer Costs:** Consumers and bulk buyers face inflated prices.
- **Logistics Challenges:** High transport costs and inefficiency in order fulfillment.
- **Information Asymmetry:** Lack of real-time market trends, demand insights, and price transparency.
- **Counterparty & Quality Risk:** Payment delays and inconsistent crop quality.

---

## 💡 The Solution

**K4kissan** is an end-to-end AI-powered agricultural marketplace designed to directly connect farmers and **Farmer Producer Organizations (FPOs)** with bulk buyers.

### ✨ Key Features

* 🤝 **Direct Connection:** Buy and sell directly without unnecessary intermediaries.
* 📦 **Collective Selling:** FPOs and smallholders aggregate supply to fulfill large bulk orders together.
* 📈 **AI Demand & Price Forecasting:** Predictive insights using `Scikit-learn` to estimate optimal harvest prices and market demand.
* 🚚 **Smart Logistics:** Integrated transporter matching, optimized routing, and live GPS tracking.
* 🔒 **Escrow Transactions:** Safe digital payments with 20% advance release and QR/OTP verification upon delivery.
* 🔍 **Quality Assurance:** AI-based photo grading, batch-level traceability, and transparent dispute resolution.

---

## 🛠️ System Architecture & Workflow

1. **Onboarding & KYC:** Multi-role authentication (Farmer, Buyer, Transporter) with location and ID verification.
2. **Listings & Matching:** Farmers list harvested/upcoming crops; buyers submit volume requirements.
3. **Price & AI Insights:** AI algorithms run quality assessment, shelf-life estimation, and fair-price indicators.
4. **Negotiation & Order Booking:** Direct price negotiations followed by 20% advance payment via secure escrow.
5. **Transport & Delivery:** Smart route assignment, QR/OTP pickup certification, and real-time shipment tracking.
6. **Verification & Settlement:** On-site quality/quantity verification triggers full escrow release.

---

## 🧰 Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React, Flutter, Tailwind CSS |
| **Backend** | Node.js, Express.js (REST APIs) |
| **Database** | MongoDB, Redis |
| **Authentication** | JWT (JSON Web Tokens) |
| **AI / ML & Automation** | Python (`scikit-learn`), n8n |

---

## 🛡️ Risk Mitigation & Feasibility

* **Low Digital Literacy:** Voice-guided navigation in local languages and intuitive, icon-based UI screens.
* **Trust & Security:** Field verification backed by Google Maps location tagging and physical crop inspection prior to dispatch.
* **Payment Assurance:** Structured escrow system paired with existing regional UPI/banking integrations.

---

## 🚀 Getting Started Locally

### Prerequisites
* [Node.js](https://nodejs.org/) (v16+ recommended)
* [MongoDB](https://www.mongodb.com/) running locally or a MongoDB Atlas URI

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/adityanathpatel/K4kissan.git](https://github.com/adityanathpatel/K4kissan.git)
   cd K4kissan
