# Dhan-Mitra: Voice-First AI Financial Companion for Rural India
## BITSoM Capstone Project - Phase 5 MVP Implementation
### Team Neural Nexus

---

## 🎯 Project Overview

**Dhan-Mitra** is a working MVP (Minimum Viable Product) that addresses financial inclusion for underserved populations in Tier III/IV cities and rural India. The platform leverages **Generative AI** and **Agentic AI** to provide simplified, voice-first financial guidance in native Indic languages.

### Target Users
- 🏍️ Gig Workers & Daily Wage Laborers
- 👨‍🌾 Farmers & Small Business Owners  
- 👩‍🏠️ Homemakers & Elderly Citizens
- 📚 Students & First-Time Earners

### Core Problem Solved
- **Financial Illiteracy**: 36% of India is financially illiterate
- **Language Barriers**: Users unable to interact with English-only financial apps
- **Lack of Trust**: Predatory lenders and opaque financial systems
- **No Digital Trail**: Underbanked users lack formal credit history

---

## ✨ MVP Features Implemented

### 1. **Voice-First Conversational Interface** ⭐ Priority 1
- Multi-turn dialogue with context awareness
- Support for 6 Indic languages (Hindi, Marathi, Gujarati, Tamil, Telugu, English)
- Knowledge base with deterministic guardrails (RAG-based)
- Intent classification system

### 2. **24/7 Financial Query Resolution** ⭐ Priority 1
Knowledge base covering:
- Bank account opening procedures
- Savings accounts & loan eligibility
- Micro-insurance options
- Investment through SIP

### 3. **Automated Government Scheme Matching** ⭐ Priority 2
6 major schemes integrated:
- Pradhan Mantri Jan Dhan Yojana (PMJDY) - Free accounts
- PM Suraksha Bima Yojana (PM-SYM) - ₹20/year insurance
- PM Shram Yogi Maan Dhan - Pension for gig workers
- PM Kisan - ₹6,000 annual farmer subsidy
- Pradhan Mantri Mudra Yojana - Up to ₹10L business loans
- Ayushman Bharat Health Account - Digital health records

### 4. **Income-Aligned Savings Nudge Engine** ⭐ Priority 2
5 types of behavioral nudges:
1. Post-income savings suggestions
2. Bill payment reminders
3. Spending analysis & alerts
4. Goal progress tracking
5. Seasonal expense preparation

### 5. **Voice-Guided Video KYC** ⭐ Priority 1
6-step mobile-first onboarding:
1. Consent collection
2. Aadhaar verification
3. OTP verification
4. Face recognition (liveness)
5. Address verification
6. Completion confirmation

### 6. **Bank Mitra Escalation System**
- Seamless human handoff for complex issues
- Ticket-based tracking
- Priority routing (High/Medium/Low)
- Multi-channel support (WhatsApp, IVR, SMS)

### 7. **User Profile Management**
- Segment classification (6 types)
- Transaction tracking & categorization
- Spending pattern analysis
- Savings goal management
- Scheme application history

---

## 🏗️ Technical Architecture

### Core Components
```
DhanMitraApp (Orchestrator)
├── ConversationalAI (Intent + Knowledge Base)
├── GovernmentSchemeMatcher (Eligibility Engine)
├── SavingsNudgeEngine (Behavioral Analytics)
├── KYCManager (6-Step Verification)
└── BankMitraEscalation (Ticket Management)
```

### Key Design Principles
✓ Privacy-first (no persistent storage)  
✓ Deterministic guardrails (RAG-based, no hallucination)  
✓ Multilingual (native languages, not translation)  
✓ Low-bandwidth (2G/3G ready)  
✓ Offline-capable (PWA architecture)  
✓ Trust-centric (Human + AI hybrid)

---

## 🎮 Demo Scenarios (6 Complete User Journeys)

1. **Gig Worker (Ramesh)**: Loan inquiry → Schemes → Savings guidance
2. **Homemaker (Lakshmi)**: Savings scheme → Goal tracking → KYC
3. **Student (Rohan)**: SIP investment → Financial literacy
4. **Farmer (Ravi)**: Government schemes discovery → Subsidies
5. **KYC Flow**: Complete 6-step verification process
6. **Bank Mitra Escalation**: Issue ticketing & resolution

---

## 🚀 How to Run

```bash
python bitsomCapstone.py
```

**Output**: 6 comprehensive demos with JSON responses showing:
- Query processing & intent classification
- Scheme recommendations & match scores
- Savings nudges & financial alerts
- KYC flow progression
- Bank Mitra ticket creation

---

## 📊 Key Metrics

**Northstar KPI**: Financial Action Conversion Rate (% users taking action/month)

Supporting Metrics:
- Voice Engagement Rate
- AA Consent Opt-in Rate  
- Loan Eligibility Match Rate
- D7 Retention Rate
- Net Promoter Score (NPS)

---

## 🔌 Production Integration Points

**Ready for integration with:**
- Bhashini API (Indic language ASR/TTS)
- UIDAI (Aadhaar verification)
- Account Aggregator Framework
- RBI regulated banks/NBFCs
- SEBI-approved investment platforms
- WhatsApp Business API
- IVR systems

---

## 📋 File Structure

```
bitsomCapstone.py     →  Main MVP (1300+ lines, 7 core modules)
README.md             →  This documentation
```

---

## 👥 Team

**Team Neural Nexus**
- Sudeep Pramanik (20%) - Product & AI Strategy
- Sulagna Raj Chaudhury (20%) - Feature Prioritization  
- Savitri Desulu (20%) - User Stories & Flows
- Kiran Raja (20%) - Testing & Methodology
- Disha Jain (20%) - Channel Strategy

---

## ✅ Phase 5 Deliverables Checklist

- ✅ Working MVP with all core features
- ✅ Voice-first conversational AI
- ✅ Government scheme engine (6 schemes)
- ✅ Savings nudge system
- ✅ KYC flow (6-step)
- ✅ Bank Mitra escalation
- ✅ Multi-language support (6 languages)
- ✅ User profile management
- ✅ 6 complete demo scenarios
- ✅ Production integration ready
- ✅ Security & compliance architecture

**Status**: 🟢 READY FOR DEMO & SUBMISSION

---

**Version**: 1.0 MVP | **Last Updated**: June 4, 2026 | **Team**: Neural Nexus
