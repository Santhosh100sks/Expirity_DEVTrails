# Expirity_DEVTrails
# Submission for the DEV Trails
# AI-Powered Points-Based Insurance for Delivery Partners

## 1. Requirement, Persona, and Application Workflow

### Persona
This solution is designed for food delivery partners working on platforms like Zomato and Swiggy. These workers depend on daily earnings and are highly affected by external disruptions such as weather, traffic, and strikes.

### Problem Requirement
Delivery partners experience income loss due to uncontrollable external conditions. The goal is to build a system that protects their earnings by providing compensation during such disruptions, using a structured and fair mechanism.

### Proposed Approach
The system introduces a points-based insurance model where delivery partners earn points through consistent work and reliability. These points act as a financial buffer and can be redeemed when income loss occurs due to verified disruptions.

### Workflow

1. User Registration  
   Delivery partner registers and subscribes to a weekly insurance plan.

2. Points Accumulation  
   Points are earned based on:
   - Number of deliveries  
   - Working hours  
   - Consistency and reliability
   - Verified activity through GPS-based tracking to ensure genuine work participation

3. Disruption Occurs  
   External events such as weather issues, traffic congestion, or strikes occur.

4. Claim Submission  
   The delivery partner reports the issue through the application by selecting the disruption type (weather, traffic, strikes, or others).
   The user can optionally upload supporting   evidence such as photos or relevant news links to strengthen the claim.
   This evidence is combined with external data sources and activity tracking to ensure accurate and fair validation.

6. Validation  
   The system validates the claim using external data and user activity.

7. Compensation  
   Points or payout is provided based on validated income loss.

---

## 2. Weekly Premium Model, Parametric Triggers, and Platform Choice

### Weekly Premium Model
The system follows a weekly subscription model aligned with gig workers’ earnings cycle.

- Premium range: ₹50 – ₹100 per week  
- Pricing is dynamic and depends on:
  - Location risk level  
  - Historical disruption frequency  

### Parametric Triggers

The system uses predefined external triggers to identify disruptions:

- Weather conditions (rain, heat, pollution)  
- Traffic congestion  
- Strikes or curfews  

### Validation Logic
A claim is approved only when:
- A disruption is detected, and  
- The worker’s activity level is significantly reduced  

### Platform Choice

Mobile application is chosen as the primary platform.

Reason:
Delivery partners primarily use smartphones, and a mobile platform enables real-time claim submission, tracking, and notifications.

---

## 3. AI/ML Integration Plan

### Risk Assessment
Machine learning models will analyze historical data to identify high-risk zones and predict potential disruptions.

### Dynamic Premium Calculation
AI models will adjust weekly premium based on:
- Location  
- Past risk patterns  
- Frequency of disruptions  

### Fraud Detection
The system will detect:
- Duplicate claims  
- Abnormal claim patterns  
- Location inconsistencies (GPS mismatch)  

### Smart Claim Validation
AI combines:
- External trigger data  
- User activity data  
to ensure that payouts are given only for genuine income loss.

---

## 4. Tech Stack and Development Plan

### Tech Stack

Frontend:
- React (Web) or Flutter (Mobile)

Backend:
- Node.js with Express

Database:
- MongoDB

AI/ML:
- Python with Scikit-learn

APIs:
- Weather API (OpenWeather)
- Mock traffic and disruption APIs

---

### Development Plan

Phase 1 (Weeks 1–2):
- Requirement analysis  
- System design  
- Basic prototype  

Phase 2 (Weeks 3–4):
- Backend development  
- Claim management system  
- Dynamic pricing implementation  

Phase 3 (Weeks 5–6):
- AI model integration  
- Fraud detection system  
- Dashboard and payout simulation  

---

## 5. Additional Considerations

- The system strictly focuses on loss of income and excludes health, vehicle, or accident-related coverage.  
- The points-based model encourages consistent work behavior while providing financial protection.  
- The design ensures fairness by relying on behavior and activity data rather than personal attributes.  
