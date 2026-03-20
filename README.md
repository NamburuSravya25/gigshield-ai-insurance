# gigshield-ai-insurance
# GigShield AI 🚀

AI-Powered Parametric Income Protection for Gig Workers

---

## 👤 Persona: Who is Our User?

Our primary user is:

**BalaRaju (Age 30)**

* Works as a Swiggy delivery partner in Vijayawada
* Works 10–12 hours/day
* Weekly earnings: ₹4000–₹7000
* No savings or financial safety net

### 🔍 Real Problem Ravi Faces:

* During heavy rain → fewer orders + unsafe driving
* During extreme heat → reduced working hours
* During high pollution → health risk → stops working
* During curfews → zero income

👉 Result: **20–30% weekly income loss**

---

## ❗ Problem Statement

Gig workers face **income volatility due to external disruptions**, but:

* No insurance covers **income loss**
* Claims systems are slow/manual
* Workers cannot afford monthly premiums

---

## 💡 Solution: GigShield AI

A **parametric insurance platform** that:

* Uses AI to calculate **weekly risk**
* Charges **low weekly premiums**
* Automatically triggers payouts when disruption thresholds are met

---

## ⚙️ System Workflow

1. **Onboarding**

   * User enters:

     * Location
     * Platform (Swiggy/Zomato)
     * Avg weekly income

2. **AI Risk Scoring**

   * Inputs:

     * Weather forecast (7-day)
     * Historical disruption data
     * Area-based risk index
   * Output:

     * Risk Score (0–1)

3. **Weekly Premium Calculation**
   Formula:
   Premium = Base Rate × Risk Score × Income Factor

4. **Policy Activation**

   * User pays weekly premium via UPI

5. **Real-Time Monitoring**

   * System tracks:

     * Rainfall
     * Temperature
     * AQI
     * Govt alerts

6. **Trigger Engine (Parametric)**

   * If threshold crossed → claim auto-triggered

7. **Instant Payout**

   * Credited directly to user (UPI)

---

## 💰 Weekly Pricing Model

| Risk Score | Premium | Coverage |
| ---------- | ------- | -------- |
| 0–0.3      | ₹20     | ₹500     |
| 0.3–0.6    | ₹40     | ₹1000    |
| 0.6–1      | ₹80     | ₹2000    |

👉 Adjusted weekly using AI predictions

---

## 📊 Parametric Triggers

| Event          | Threshold     | Payout Logic |
| -------------- | ------------- | ------------ |
| Heavy Rain     | >50mm/day     | ₹300/day     |
| Extreme Heat   | >42°C         | ₹250/day     |
| High Pollution | AQI >300      | ₹200/day     |
| Curfew         | Govt Declared | ₹500/day     |

---

## 📉 Market Crash Scenario (IMPORTANT)

### Problem:

Sudden drop in orders due to:

* Platform outages
* Demand crashes
* Economic slowdown

### Solution:

We introduce **Demand Index Monitoring**:

* Inputs:

  * Order volume trends (mock API)
  * Platform activity data

### Trigger:

* If order volume drops >40% vs weekly average

### Action:

* Compensation payout triggered

👉 Ensures protection beyond environmental risks

---

## 🤖 AI/ML Architecture

### 1. Risk Prediction Model

* Model Type: Regression / Classification
* Inputs:

  * Weather forecast
  * Location
  * Historical disruptions
* Output:

  * Weekly risk score

---

### 2. Fraud Detection System

* 📍 GPS Validation

  * Checks if user is in affected area

* 🔁 Duplicate Claim Detection

  * Prevents multiple claims for same event

* 📉 Anomaly Detection

  * Flags:

    * Too frequent claims
    * Claims without real disruption

---

## 🏗️ Technical Architecture

### Frontend:

* React.js (Mobile-first UI)

### Backend:

* Node.js + Express

### AI Layer:

* Python microservice (Flask)

### Database:

* Firebase / MongoDB

### APIs:

* Weather API (OpenWeather / mock)
* Location API (Google Maps)
* Payment API (Razorpay sandbox)

---

## 🔄 System Architecture Flow

Frontend → Backend → AI Service → Trigger Engine → Payment System

---

## 📱 Platform Choice

Mobile-first Progressive Web App (PWA)

Why:

* No installation required
* Works on low-end devices
* Fast access for gig workers

---

## 📊 Dashboard Features

* Weekly income vs protected income
* Risk level visualization
* Claim history
* Active coverage

---

## 🎯 Future Roadmap

* Real API integrations
* Advanced ML models
* Partner with gig platforms
* Scale to multiple cities

---

## 🎥 Demo Video

