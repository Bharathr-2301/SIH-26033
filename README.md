# Smart India Hackathon Workshop
# Date: 24/11/2026
## Reference Number: 26018941
## Name: Bharath R

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

# 🌾 KisanSetu

### Direct Farm-to-Market Digital Ecosystem for Transparent Agricultural Trade

**Smart India Hackathon 2026 | Problem Statement ID: SIH 26033**

**Theme:** Agriculture, FoodTech & Rural Development

---

## 📌 1. Project Overview

**KisanSetu** is a direct-to-buyer digital agricultural platform designed to connect individual farmers and Farmer Producer Organizations (FPOs) directly with retailers, institutional buyers, and everyday consumers—eliminating unnecessary intermediaries at every stage of the supply chain.

In traditional agricultural markets, produce passes through multiple middlemen, resulting in lower earnings for farmers and inflated prices for consumers. KisanSetu introduces a transparent, low-bandwidth, voice-accessible marketplace that combines mandi-linked fair-price discovery, village-level order pooling, QR traceability, and escrow-backed UPI payments to build an equitable and sustainable agricultural ecosystem.

## 🏢 2. Problem Statement Details

| Category | Details |
| --- | --- |
| Problem ID | SIH 26033 |
| Problem Title | Multiple intermediaries reduce farmers' earnings and increase consumer prices |
| Organization | Ministry of Consumer Affairs, Food & Public Distribution |
| Theme | Agriculture, FoodTech & Rural Development |
| Competition | Smart India Hackathon 2026

 |

## ❗ 3. Problem Identification

Farmers form the backbone of the agricultural supply chain, yet they retain only a small fraction of the final price paid by consumers.

### Major Challenges

* **Multiple Intermediaries:** Cascading commissions across middlemen reduce farmer profits and inflate retail prices.
* **Lack of Fair-Price Awareness:** Limited access to live mandi rates forces small farmers into distress sales.
* **High Logistics Costs:** Small and marginal farmers cannot afford independent transportation for bulk orders.
* **Post-Harvest Spoilage:** Repeated loading, unloading, and delays across multiple mandis degrade perishable produce.
* **Low Digital Literacy & Connectivity:** Complex apps and poor rural internet hinder farmer adoption.
* **Trust & Payment Delays:** Delayed settlements and quality disputes discourage direct trading.

## 💡 4. Proposed Solution

KisanSetu provides a lightweight, mobile-friendly digital marketplace that enables farmers to sell directly to buyers with transparent pricing, pooled logistics, and instant digital payouts.

### Core Solution Components

1. Direct Produce Listing & Transparent Bidding
2. Fair-Price Discovery Engine (Benchmarked to Live Mandi Rates)
3. Smart Demand-Supply Matching
4. FPO & Village Cluster Order Aggregation
5. Shared Logistics & Pickup Coordination
6. QR-Based Farm-to-Table Produce Traceability
7. Voice-First Regional Language Interface & Escrow UPI Payments

## 🚀 5. Key Features

### 👨‍🌾 Farmer Module

* Quick OTP-based phone registration and login.
* Voice-assisted crop listing in regional Indian languages.
* Upload produce details with quantity, quality grade, and base price.
* Receive fair minimum selling price recommendations.
* Pool produce with nearby farmers via FPO clusters to fulfil bulk orders.
* Receive SMS/WhatsApp order alerts and instant UPI payouts.

### 🛒 Buyer & Consumer Module

* Browse and filter fresh produce directly from verified farmers and FPOs.
* Compare prices and place direct orders or transparent bids.
* Scan QR batch codes to verify farm origin, harvest date, and quality grade.
* Secure checkout via UPI (Razorpay) with escrow protection.
* Track order and delivery status in real time.

### 🤖 Price, Demand & Logistics Module

**1. Fair-Price Discovery**

Recommends fair selling prices using:

* Live and historical mandi rates (AGMARKNET / e-NAM).
* Crop category and quality grade.
* Regional supply and seasonal trends.

**2. Demand-Supply Matching**

Matches farmers with nearby bulk buyers, retailers, and local consumers based on crop availability, freshness window, and distance to shorten transit times.

**3. Shared Logistics Dispatch**

Coordinates village-level pooled pickups and shared transport vehicles using OpenStreetMap to cut per-kilogram freight costs and reduce spoilage.

### 📊 FPO & Admin Dashboard

* Verify farmer and buyer accounts.
* Manage village cluster aggregations and pooled shipments.
* Monitor active listings, orders, and escrow transactions.
* Track marketplace analytics and resolve quality disputes.

## 🏗️ 6. System Architecture

KisanSetu follows a lightweight, modular architecture optimized for basic smartphones and low-connectivity rural networks.

```text
             FARMERS / FPOs
                    |
                    |
          WEB APPLICATION (PWA)
        (React.js + Tailwind CSS)
                    |
          -----------------------
          |                     |
     FARMER MODULE         BUYER MODULE
     (Voice + OTP)       (Browse + QR Scan)
          |                     |
          ----------- -----------
                    |
              BACKEND SERVER
           (Node.js + Express.js)
                    |
      ---------------------------------
      |               |               |
   DATABASE     PRICE & DEMAND     PAYMENTS
  (Firebase /      ANALYSIS         (UPI /
   MongoDB)    (Python + Sklearn)  Razorpay)
                      |
             -------------------
             |                 |
       FAIR-PRICE         LOCATION &
       SUGGESTION      LOGISTICS ROUTING
                        (OpenStreetMap)
                      |
              DIRECT MARKETPLACE
                      |
             CONSUMERS / BUYERS

```

## 🔄 7. Working Process

1. Farmers log in securely using Firebase Phone OTP.
2. Farmers list available crops using a simple form or voice-assisted regional interface.
3. The system suggests a fair selling price based on mandi data and demand analysis.
4. Nearby consumers, retailers, and bulk buyers browse listings and place orders directly.
5. Buyers complete payment securely via UPI (Razorpay).
6. Pooled pickup and delivery are coordinated via OpenStreetMap.
7. Upon delivery confirmation, the farmer receives an instant payout.

## 🛠️ 8. Technology Stack

### Frontend Development

* React.js
* Tailwind CSS

### Backend Development

* Node.js
* Express.js

### Database

* Firebase / MongoDB

### Price & Demand Analysis

* Python
* Scikit-learn

### Maps, Auth & Payments

* OpenStreetMap (Maps & Location)
* Firebase Phone OTP (User Login)
* Razorpay / UPI (Digital Payments)

### Hosting & Development Tools

* Vercel (Frontend Hosting)
* Render (Backend Hosting)
* Visual Studio Code, Git, GitHub

## 🎯 9. Project Objectives

* Eliminate unnecessary intermediaries between farmers and buyers.
* Increase farmer earnings through fair-price discovery and instant UPI payouts.
* Make fresh agricultural produce more affordable for consumers.
* Empower small and marginal farmers through FPO cluster pooling.
* Ensure rural accessibility via a lightweight, voice-first regional interface.
* Reduce post-harvest wastage and freight costs through shared logistics.

## 🌍 10. Expected Impact

### Benefits for Farmers

* Higher share of the final consumer price.
* Protection from distress sales via fair-price benchmarks.
* Verifiable digital transaction history for formal credit and crop insurance.
* Lower transport costs through village-level order pooling.

### Benefits for Consumers

* Lower retail prices without cascading middleman markups.
* Fresher produce with shorter farm-to-table transit times.
* Transparent origin and harvest details via QR traceability.

### Benefits for the Agricultural Sector

* Reduced post-harvest spoilage and lower transport emissions.
* Stronger FPO networks and digital rural infrastructure.
* Transparent, data-driven agricultural supply chain.

## 🔮 11. Future Enhancements

* Offline-first Progressive Web App (PWA) syncing for zero-network areas.
* Direct API integration with e-NAM and state mandi price feeds.
* Dedicated Android/iOS mobile applications.
* Cold-chain and local warehouse availability tracking.
* Integration with government farmer welfare schemes and crop insurance portals.

## 🔐 12. Security & Reliability

* OTP-based phone authentication via Firebase Auth.
* Role-based access control for Farmers, FPOs, Buyers, and Admins.
* Escrow-backed UPI payments to prevent fraud and payment delays.
* Photo-verified quality checks at pickup to minimize delivery disputes.
* Encrypted API communication and regular database backups.

## 👥 13. Team & Contributors

This project is developed as part of **Smart India Hackathon 2026** by **Siva Ganesh N** (Ref: 26011005).

## 🤝 14. Contribution Guidelines

Contributions are welcome!

1. Fork this repository.
2. Create a new feature branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch to GitHub.
6. Submit a Pull Request.

## 📜 15. License

This project is developed for educational and innovation purposes as part of Smart India Hackathon 2026.

---

## 🌱 Our Vision

**"Empowering Farmers with Technology, Eliminating Unnecessary Intermediaries, and Building a Transparent Agricultural Ecosystem."**

**Together, let's create a smarter and fairer future for agriculture.** 🌾
