# GigShield-AI – AI-Powered Income Protection for Delivery Partners

Protecting gig workers from income loss caused by real-world disruptions.

---

## The Problem

### Rain Problem in Numbers

#### Mumbai (Worst Affected)

| Month | Rainy Days | Avg Income Loss |
|------|----------|----------------|
| June | 12–15 days | ₹5,000–6,500 |
| July | 20–25 days | ₹8,000–10,000 |
| August | 18–22 days | ₹7,000–9,000 |
| September | 10–12 days | ₹4,000–5,000 |

#### Chennai

| Month | Rainy Days | Avg Income Loss |
|------|----------|----------------|
| October | 10–12 days | ₹4,000–5,000 |
| November | 12–15 days | ₹5,000–6,000 |
| December | 8–10 days | ₹3,200–4,000 |

---

## The Human Impact

A typical rainy day for a delivery partner:

```
5:00 AM – Checks weather  
6:00 AM – Starts work  
9:00 AM – Heavy rain begins  
10:00 AM – Orders stop  
11:00 AM – Takes shelter  
2:00 PM – No orders  
4:00 PM – Goes home  
6:00 PM – Rain stops (peak time missed)  

Result → ₹0 earned, ₹200 spent
```

---

## Current Gaps

| Option | Problem |
|------|--------|
| Government Schemes | Not for gig workers |
| Traditional Insurance | Complex + monthly |
| Platform Support | No compensation |
| Savings | Not possible |
| Moneylenders | High interest |

---

## Persona: Rajesh Kumar

- Age: 28  
- City: Mumbai (Andheri East)  
- Platform: Swiggy  
- Income: ₹18,000–₹22,000/month  

Needs automatic income protection.

---

# Solution: GigShield-AI

---

## How It Works (Simple Flow)

```
Sign Up → Pay Weekly → Rain ≥25mm → Auto Detection → ₹300 Payout
```

---

## Key Differentiators

| Feature | GigShield-AI | Traditional Insurance |
|--------|-------------|----------------|
| Focus | Only rain | Everything |
| Premium | Weekly ₹35–55 | Monthly ₹500+ |
| Claim | Automatic | Manual |
| Time | < 60 sec | 15–30 days |
| Effort | Zero | High |

---

# Complete Workflow

---

## Registration (2 Minutes)

User enters:
- Phone number  
- Name  
- City + Pincode  
- Vehicle  
- UPI ID  

Backend process:
- Device fingerprinting  
- Risk score calculation  
- Premium calculation  

---

## Weekly Premium

```
Weekly Premium = Base (₹40)
               + City Risk (₹0–10)
               + Pincode Risk (₹0–10)
               + Seasonal Factor (₹0–5)
               + Forecast Factor (₹0–10)
               - Trust Discount (₹0–5)
```

Example (Mumbai, July):

```
40 + 10 + 10 + 5 + 8 – 5 = ₹55
```

---

## Rain Monitoring (24/7)

System checks weather using:
- OpenWeatherMap  
- WeatherAPI  
- IMD  

```
If rainfall ≥ 25mm within 3 hours → Claim triggered
```

---

## Auto Claim Generation

- Rain detected  
- Location verified  
- Fraud checks executed  
- Claim approved  

Processing time: ~5 minutes  

---

## Instant Payout

- ₹300 credited via UPI  
- Time: < 60 seconds  
- Notification via SMS and WhatsApp  

---

# AI Strategy

---

## Risk Prediction

AI predicts:
- Rain probability  
- Income loss risk  

---

## Dynamic Pricing

- High risk → Higher premium  
- Low risk → Lower premium  

---

## Fraud Detection

1. Identity verification  
2. Location validation  
3. Weather verification  
4. Pattern detection  
5. Network fraud detection  
6. Behavioral tracking  

---

# Why GigShield-AI is Unique

- Focuses only on rain-based income loss (high accuracy)
- Uses parametric insurance (no claims, instant payout)
- Weekly micro-pricing (affordable for gig workers)
- Fully automated system (zero user effort)
- Multi-layer fraud detection ensures reliability
- Designed as a user-friendly application for easy access and seamless experience

---

# Rain Trigger System

- Threshold: ≥25mm rainfall (3 hours)  
- Active time: 8 AM – 10 PM  
- Maximum payouts: 8 per month  

---

# Technical Architecture

```
Frontend (React PWA)
        ↓
Backend (Node.js)
        ↓
MongoDB + Redis
        ↓
Microservices:
  - Weather Service
  - Fraud Detection Service
  - Payment Service
        ↓
External APIs:
  - OpenWeatherMap
  - Razorpay
  - Twilio
```

---

# Tech Stack

| Layer | Technology |
|------|-----------|
| Frontend | React.js (PWA) |
| Backend | Node.js + Express |
| Database | MongoDB |
| Cache | Redis |
| Weather | OpenWeather API |
| Payments | Razorpay |
| Notifications | Twilio |
| Hosting | Vercel + Render |

---

# Business Model

| Item | Amount |
|------|--------|
| Premium | ₹180 |
| Claims | ₹150 |
| Cost | ₹37 |
| Profit | ₹38 |

---

# Roadmap

### Phase 1
- Research  
- Documentation  

### Phase 2
- UI + Backend  

### Phase 3
- AI + Automation  

---

# Team

- Tejasrinithi U S – System Architect & Project Lead  
- Dhanushree S – Backend Developer (API & Database)  
- Dharana Nidhini K K – Frontend Developer (UI/UX Design)  
- Merlin Praisy S – AI/ML Developer (Risk Prediction & Fraud Detection)  
- Sarmila V – Research & Documentation (Business Model & Analysis)

---

# Links

- Demo Video: [Add link]  
- GitHub: [Add link]  

---

# Conclusion

GigShield-AI provides automatic financial protection for delivery partners during heavy rain.

- Instant payouts  
- Zero effort  
- Simple pricing  
- Scalable solution  
