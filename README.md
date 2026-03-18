# QuickShield 🛡️
### AI-Powered Income Protection for Grocery Delivery Workers

QuickShield is a parametric insurance platform that automatically detects disruptions — heavy rain, extreme heat, app downtime, and more — and instantly compensates grocery delivery workers (Zepto, Blinkit, Instamart) without requiring manual claims.

---

## 👥 Team: Attackers

| Name | Role |
|---|---|
| Akash Vivian S | Lead |
| Dinesh S | Member |
| Sri Vignesh S | Member |
| Datchan K R | Member |

---

## ❗ Problem Statement

Grocery delivery workers depend entirely on daily earnings. Disruptions like heavy rain, extreme heat, high pollution, local restrictions, or app downtime can wipe out their income with zero safety net.

---

## 💡 Solution

QuickShield uses AI-based risk assessment, parametric insurance triggers, fraud detection, and an instant payout system to automatically compensate workers when disruptions occur — no paperwork, no waiting.

---

## ⚡ Parametric Triggers

Claims are auto-approved when any of the following thresholds are crossed:

| Condition | Threshold |
|---|---|
| Rainfall | > 40 mm |
| Temperature | > 42°C |
| AQI | > 300 |
| Orders | < 10 |
| App downtime | Detected |

---

## 💰 Pricing Model

Weekly premium is dynamically calculated based on weather, location risk, and order activity:

| Risk Level | Weekly Premium |
|---|---|
| Low | ₹25 |
| Medium | ₹40 |
| High | ₹60 |

---

## 🤖 AI/ML Details

- **Model:** Linear Regression (extendable to Random Forest / XGBoost)
- **Training data:** Synthetic dataset
- **Input features:** Rain, Temperature, AQI, Order count
- **Output:** Weekly premium prediction

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript (or React) |
| Backend | Python (Flask) |
| ML | Scikit-learn, Pandas, Joblib |
| APIs | OpenWeatherMap (or Mock) |
| Database | Firebase / Local storage |
| Payments | Razorpay (Test Mode) |

---

## 📂 Project Structure

```
quickshield/
├── backend/
│   ├── app.py
│   ├── model.py
│   └── utils.py
├── frontend/
│   ├── index.html
│   └── dashboard.html
├── model/
│   ├── train_model.py
│   └── premium_model.pkl
├── data/
│   └── data.csv
└── requirements.txt
```

---

## ▶️ Getting Started

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Train the ML model
```bash
python model/train_model.py
```

### 3. Start the backend
```bash
python backend/app.py
```

### 4. Open the frontend
Open `frontend/index.html` in your browser.

---

## 🧪 Sample Input / Output

**Input:**
```
Rain:        50 mm
Temperature: 41°C
AQI:         320
Orders:      5
```

**Output:**
```
Premium:  ₹50–₹70/week
Claim:    Approved ✅
Payout:   ₹300
```

---

## 🔄 System Workflow

```
User registers → AI calculates premium → User subscribes
      ↓
Real-time monitoring → Disruption detected → Claim auto-triggered
      ↓
Fraud checks → Instant payout → Dashboard updated
```

---

## 📊 Dashboard Features

- Weekly premium display
- Current risk level
- Claim status
- Earnings protected summary

---

## 🎯 Future Enhancements

- Real-time weather & order API integration
- Advanced ML models (Random Forest, XGBoost)
- Mobile app version
- Live GPS tracking
- Blockchain-based claim validation

---

## 📽️ Demo

> _(Attach your demo video link here)_

---

## 📜 License

This project was built for hackathon purposes. All rights reserved by Team Attackers.
