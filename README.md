# 🛡️ KAVACH
### Vedic-Grounded Threat Classifier for Rural India

> *"Satyameva Jayate" — Truth alone triumphs. Protect the vulnerable from digital deception.*

**KAVACH** (कवच — armor/shield) is an offline SMS and WhatsApp phishing detection system designed for rural Indian users — farmers, elderly, and first-time smartphone users — who are most vulnerable to financial fraud and digital scams.

---

## 🎯 The Problem

Rural India is experiencing an explosion of **digital financial fraud** via SMS and WhatsApp:
- Fake KCC loan offers
- Fraudulent PM-Kisan scheme messages
- OTP theft via social engineering
- Fake government subsidy links

KAVACH classifies these threats **offline** using Vedic epistemological logic.

---

## 🧠 How It Works

KAVACH applies **Nyaya Pramana** (Nyaya school of valid knowledge) to classify messages:

| Pramana Test | What It Checks |
|---|---|
| **Pratyaksha** (direct) | Is the URL real? Does sender match? |
| **Anumana** (inference) | Urgency patterns, pressure language |
| **Upamana** (comparison) | Similarity to known phishing templates |
| **Shabda** (testimony) | Is this from a verified government source? |

---

## 📊 Current Performance

| Metric | Value |
|---|---|
| Phishing detection rate | 50% |
| False positive rate | 0% |
| Model size | < 10MB |
| Internet required | No |
| Languages | Hindi, Bengali, English |

> Honest benchmarks. We report what works, not what sounds impressive.

---

## 🏗️ Architecture

```
Input SMS/WhatsApp Text
        │
        ▼
┌───────────────────┐
│  KAVACH Classifier│
│  (Nyaya Logic)    │
├───────────────────┤
│  Feature Extract  │  ← URL patterns, urgency words
│  Pramana Score    │  ← 4-source confidence weighting
│  Threshold Gate   │  ← Safe / Suspicious / Phishing
└───────────────────┘
        │
        ▼
Alert + Explanation (in local language)
```

---

## 🚀 Quick Start

```bash
git clone https://github.com/divinesouljoy-cmd/KAVACH.git
cd KAVACH
pip install -r requirements.txt --break-system-packages

# Test on a sample message
python3 kavach.py --text "Congratulations! Your PM-Kisan payment of Rs.6000 is pending. Click here to claim: bit.ly/xxxxx"
```

**Output:**
```
🛡️ KAVACH Analysis
Pramana Score: 0.23 (LOW TRUST)
Classification: PHISHING
Reason: Urgency trigger + shortened URL + unverified sender
```

---

## 🌾 Target Users

- Farmers receiving fake KCC / PMFBY scheme messages
- Rural elderly using WhatsApp for the first time
- Self-Help Group (SHG) members in Barak Valley, Assam

---

## 🗺️ Roadmap

- [x] Core Nyaya classification engine
- [x] Hindi / Bengali keyword detection
- [x] Zero false positive baseline
- [ ] WhatsApp Bot integration
- [ ] Assamese language support
- [ ] 80%+ detection rate target
- [ ] Offline Android APK

---

## 🏢 Organization

**Divine Earthly**
UDYAM-AS-05-0000684 | Silchar, Assam, India
GitHub: [divinesouljoy-cmd](https://github.com/divinesouljoy-cmd)

---

## 📜 License

MIT — Shield the vulnerable. Knowledge protects.
