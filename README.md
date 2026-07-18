<div align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-0.100+-green.svg" alt="FastAPI">
  <img src="https://img.shields.io/badge/React-18.0+-cyan.svg" alt="React">
  <img src="https://img.shields.io/badge/DoWhy-0.11+-orange.svg" alt="DoWhy">
  <img src="https://img.shields.io/badge/EconML-0.14+-red.svg" alt="EconML">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License">
</div>

<br>

<div align="center">
  <h1>🚀 Enterprise Causal AI Decision Engine</h1>
  <h3><em>Beyond Prediction — From Correlation to Causation</em></h3>
</div>

---

## 📖 Table of Contents
- [Overview](#overview)
- [Why This Project?](#why-this-project)
- [Key Features](#key-features)
- [Architecture](#architecture)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Causal Methods](#causal-methods)
- [UI/UX Design](#uiux-design)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🔍 Overview

The **Enterprise Causal AI Decision Engine** is a next-generation decision intelligence platform that goes beyond traditional predictive analytics to **identify cause-and-effect relationships** and **estimate the impact of business interventions**. 

While conventional AI stops at correlations, this engine maps **cause and effect**, delivering predictions that are **explainable, actionable, and profitable**.

### 🎯 Core Philosophy
> "Traditional ML predicts what will happen. Causal AI predicts what will happen if we intervene."

This project empowers organizations to answer the most critical business question: **"What would happen if we changed X?"** — enabling data-driven decisions with confidence.

---

## ❓ Why This Project?

### The Problem with Traditional AI
- ❌ Predictive models only show correlations
- ❌ Cannot answer "what-if" scenarios
- ❌ Black-box decisions with no explanation
- ❌ Vulnerable to confounding variables

### The Causal AI Solution
- ✅ Identifies true cause-and-effect relationships
- ✅ Simulates interventions before implementation
- ✅ Provides explainable, auditable decisions
- ✅ Robust to confounders and bias

### Market Context
- 📈 Causal AI market projected to reach **$456.8M by 2030**
- 📈 Growing at **41.8% CAGR**
- 📈 Critical for modern enterprise decision-making

---

## ✨ Key Features

### 📊 **Data Management**
- 🔹 Upload CSV, Excel, and JSON files
- 🔹 Automatic data validation and cleaning
- 🔹 Interactive data preview and statistics
- 🔹 Feature selection and type detection
- 🔹 Data transformation pipelines

### 🧠 **Causal Inference**
- 🔹 **DoWhy** — Graphical causal models with refutation tests
- 🔹 **EconML** — Machine learning-based causal estimation
- 🔹 **Bayesian Networks** — Probabilistic causal reasoning
- 🔹 **Causal Discovery** — Automatic structure learning from data
- 🔹 **Treatment Effect Estimation** — ATE, CATE, and personalized effects

### 🎮 **Intervention Simulation**
- 🔹 What-if scenario builder
- 🔹 Real-time effect estimation
- 🔹 Confidence intervals and uncertainty quantification
- 🔹 Sensitivity analysis and robustness checks
- 🔹 Individualized treatment effects (CATE)

### 🤖 **AI Assistant (Gemini)**
- 🔹 Natural language causal queries
- 🔹 Automated method selection
- 🔹 Plain-language interpretation of results
- 🔹 Actionable business recommendations
- 🔹 Interactive chat interface

### 📈 **Visualizations**
- 🔹 Interactive causal DAG builder
- 🔹 Treatment effect plots with confidence bands
- 🔹 Sensitivity analysis visualizations
- 🔹 Comprehensive results dashboard
- 🔹 Exportable charts and graphs

### 📄 **Reporting**
- 🔹 Automated report generation
- 🔹 Export to PDF, CSV, and JSON
- 🔹 Shareable analysis links
- 🔹 Audit trail of all decisions

---

## 🏗️ Architecture


---

## 🛠️ Tech Stack

### **Backend**
| Component | Technology | Version |
|-----------|------------|---------|
| Framework | FastAPI | 0.100+ |
| ORM | SQLAlchemy | 2.0+ |
| Database | PostgreSQL / SQLite | - |
| Causal Inference | DoWhy | 0.11+ |
| Causal ML | EconML | 0.14+ |
| Bayesian Networks | pgmpy | 0.1+ |
| AI Integration | Google Gemini API | latest |
| Data Processing | Pandas, NumPy | latest |
| Visualization | Plotly, Matplotlib | latest |
| Migration | Alembic | latest |
| Validation | Pydantic | 2.0+ |

### **Frontend**
| Component | Technology | Version |
|-----------|------------|---------|
| Framework | React | 18.0+ |
| Build Tool | Vite | 4.0+ |
| State Management | Redux Toolkit | 1.9+ |
| Styling | Tailwind CSS | 3.0+ |
| UI Components | Material-UI / Chakra | latest |
| HTTP Client | Axios | 1.0+ |
| Data Fetching | React Query | 4.0+ |
| Visualization | D3.js, Plotly | latest |
| Forms | React Hook Form | 7.0+ |

### **DevOps**
- Docker & Docker Compose
- Kubernetes (optional)
- GitHub Actions (CI/CD)
- Nginx (reverse proxy)

---

## 🚀 Getting Started

### **Prerequisites**
- Python 3.9+
- Node.js 16+
- npm or yarn
- Git
- (Optional) Docker & Docker Compose

### **1. Clone the Repository**
```bash
git clone https://github.com/vishakha2121/Enterprise-Causal-AI-Decision-Engine.git
cd Enterprise-Causal-AI-Decision-Engine

cd backend
python -m venv venv

# On Windows
venv\Scripts\activate

# On Mac/Linux
source venv/bin/activate


cd frontend
npm install