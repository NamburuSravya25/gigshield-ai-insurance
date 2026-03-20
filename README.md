# GigShield AI 🚀

AI-Powered Parametric Income Protection for Gig Workers

---

## 👤 Persona: Who is Our User?

Our primary user is:

**Ravi (Age 26)**

* Works as a Swiggy delivery partner in Vijayawada
* Works 10–12 hours/day
* Weekly earnings: ₹4000–₹7000
* No savings or financial safety net

### 🔍 Real Problem Ravi Faces:

* During heavy rain → fewer orders + unsafe working conditions
* During extreme heat → reduced working hours
* During high pollution → forced to stop working
* During curfews → zero income

👉 Result: **20–30% weekly income loss**

---

## 📍 Local Context: Vijayawada

In Vijayawada:

* 🌡️ Summers often exceed **42–45°C**, reducing working hours
* 🌧️ Monsoon rains lead to waterlogging and unsafe delivery conditions
* 🚦 Traffic congestion delays deliveries
* 🌫️ Pollution spikes in busy areas

👉 These conditions frequently cause **significant weekly income loss for delivery partners**

---

## ❗ Problem Statement

Gig workers face **income volatility due to external disruptions**, but:

* No insurance covers **loss of income**
* Claims systems are manual and slow
* Workers cannot afford monthly premiums

---

## 💡 Solution: GigShield AI

A **parametric insurance platform** that:

* Uses AI to calculate **weekly risk**
* Charges **affordable weekly premiums**
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

     * **Risk Score (0–1)**

3. **Weekly Premium Calculation**

   * Formula:
     **Premium = Base Rate × Risk Score × Income Factor**

4. **Policy Activation**

   * User pays weekly premium via UPI

5. **Real-Time Monitoring**

   * System tracks:

     * Rainfall
     * Temperature
     * AQI
     * Government alerts

6. **Trigger Engine (Parametric)**

   * If threshold is crossed → claim is automatically triggered

7. **Instant Payout**

   * Amount credited directly to user via UPI

---

## 💰 Weekly Pricing Model

| Risk Score | Premium | Coverage |
| ---------- | ------- | -------- |
| 0–0.3      | ₹20     | ₹500     |
| 0.3–0.6    | ₹40     | ₹1000    |
| 0.6–1      | ₹80     | ₹2000    |

👉 Premiums are dynamically adjusted every week using AI predictions

---

## 📊 Parametric Triggers

| Event          | Threshold     | Payout Logic |
| -------------- | ------------- | ------------ |
| Heavy Rain     | >50mm/day     | ₹300/day     |
| Extreme Heat   | >42°C         | ₹250/day     |
| High Pollution | AQI >300      | ₹200/day     |
| Curfew         | Govt Declared | ₹500/day     |

---

## 📉 Market Crash Scenario (Demand Drop Protection)

### Problem:

Delivery partners may lose income due to:

* Platform outages
* Sudden drop in customer demand
* Economic slowdowns

### Solution:

We introduce a **Demand Index Monitoring System**

* Inputs:

  * Order volume trends (mock API)
  * Platform activity data

### Trigger:

* If demand drops **>40% compared to weekly average**

### Action:

* Automatic payout triggered

👉 Ensures coverage beyond environmental disruptions

---

## 🤖 AI/ML Architecture

### 1. Risk Prediction Model

* Model Type: Regression / Classification
* Inputs:

  * Weather forecast
  * Location (city-specific data like Vijayawada)
  * Historical disruption frequency
* Output:

  * **Weekly Risk Score (0–1)**

👉 This score directly drives premium pricing and risk classification

---

### 2. Fraud Detection System

* 📍 GPS Validation

  * Ensures user is present in affected area

* 🔁 Duplicate Claim Detection

  * Prevents repeated claims for same event

* 📉 Anomaly Detection

  * Flags:

    * Unusual claim frequency
    * Claims without actual disruption

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

## 🧪 Prototype (Phase 1 Scope)

In this phase, we have developed:

* Complete system workflow
* AI-based pricing logic
* Parametric trigger definitions
* Technical architecture design

👉 This forms the foundation for implementation in upcoming phases

---

## 🎯 Future Roadmap

* Integrate real APIs
* Build AI models
* Implement real-time trigger engine
* Enable live payouts
* Expand across multiple cities

---

## 🎥 Demo Video

(Add your video link here)
