<p align="center">
  <img src="https://raw.githubusercontent.com/Dexter-Cyber-Ai/.github/main/profile/assets/banner.png"
       width="850"
       alt="Dexter Cyber AI Banner" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Machine%20Learning-0A0A0A?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Cyber-Security-111827?style=for-the-badge&logo=hackthebox&logoColor=green" />
  <img src="https://img.shields.io/badge/Python-Backend-1f2937?style=for-the-badge&logo=python&logoColor=yellow" />
</p>

<p align="center">
<b>Dexter AI</b> is a hybrid cyber defense system that combines  
<b>signature-based intrusion detection</b> with  
<b>machine-learning-driven anomaly detection</b>.
</p>

# Dexter AI – Phase 1

Dexter AI is a hybrid network security system that combines
signature-based intrusion detection systems (IDS) with
machine learning–based anomaly detection.

This repository contains Phase 1 (MVP) of the project,
focused on network-level threat detection.

---

## 🎯 Phase 1 Goal (MVP)

Build a hybrid network defense module that:

- Detects known attacks using signature-based IDS (Suricata)
- Detects unknown / zero-day behaviors using ML-based anomaly detection
- Collects, processes and analyzes network traffic in a simulated environment
- Produces structured outputs for monitoring and future automation

---

## ✨ Core Capabilities
*(Seviye 2 – Feature Grid)*

- 🧠 **ML-Based Anomaly Detection**  
  Learns normal network behavior and flags deviations in real time.

- 🛡️ **Signature-Driven IDS Engine**  
  Uses Suricata to detect known attack patterns and threats.

- 📡 **Network Traffic Simulation & Analysis**  
  Full traffic generation and monitoring in a controlled environment.

- ⚙️ **Modular & Extensible Architecture**  
  Designed to evolve into autonomous detection and response systems.

---

## 🧩 Core Components

### Infrastructure Simulation
- Docker-based enterprise network simulation
- Internal and external network segments
- User nodes, servers and attacker simulation

### IDS Layer
- Suricata for signature-based detection
- Alert and traffic log generation

### Data Pipeline
- Log collection in JSON format
- Feature extraction and preprocessing
- Dataset generation for ML training

### Machine Learning
- Anomaly detection models
- Normal vs suspicious traffic learning
- Risk scoring (Phase 1 prototype)

---

## 🛠️ Technologies

- Python
- Docker & Docker Compose
- Suricata IDS
- Pandas, NumPy
- Scikit-learn

---

## 🗺️ Roadmap
*(Seviye 2 – Startup hissi veren kısım)*

- ✅ **Phase 1** – Network IDS MVP  
- 🟡 **Phase 2** – Behavioral Analysis & Advanced ML Models  
- 🔲 **Phase 3** – Autonomous Response & Adaptive Defense

---

## 📌 Project Status

This project is currently under active development.

Phase 1 focuses on building a working MVP with:
- Infrastructure simulation
- IDS integration
- Initial ML pipeline

Advanced features such as eBPF-based monitoring,
self-learning models and automated response mechanisms
are planned for future phases.

---

## 📁 Repository Structure
