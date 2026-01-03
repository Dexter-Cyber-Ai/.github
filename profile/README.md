<p align="center">
  <img src="https://raw.githubusercontent.com/Dexter-Cyber-Ai/.github/main/profile/assets/banner.png"
       width="1000"
       alt="Dexter Cyber AI Banner" />
</p>

# Dexter AI – Phase 1

Dexter AI is a hybrid network security system that combines
signature-based intrusion detection systems (IDS) with
machine learning–based anomaly detection.

This repository contains Phase 1 (MVP) of the project,
focused on network-level threat detection.

---

## Phase 1 Goal (MVP)

Build a hybrid network defense module that:

- Detects known attacks using signature-based IDS (Suricata)
- Detects unknown / zero-day behaviors using ML-based anomaly detection
- Collects, processes and analyzes network traffic in a simulated environment
- Produces structured outputs for monitoring and future automation

---

## Core Components

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

## Technologies

- Python
- Docker & Docker Compose
- Suricata IDS
- Pandas, NumPy
- Scikit-learn

---

## Project Status

This project is currently under active development.

Phase 1 focuses on building a working MVP with:
- Infrastructure simulation
- IDS integration
- Initial ML pipeline

Advanced features such as eBPF-based monitoring,
self-learning models and automated response mechanisms
are planned for future phases.

<p align="center">
  <img src="https://img.shields.io/badge/AI-Machine%20Learning-0A0A0A?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Cyber-Security-111827?style=for-the-badge&logo=hackthebox&logoColor=green" />
  <img src="https://img.shields.io/badge/Python-Backend-1f2937?style=for-the-badge&logo=python&logoColor=yellow" />
</p>

## Repository Structure

