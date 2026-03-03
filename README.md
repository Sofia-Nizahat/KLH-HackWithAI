# 💼 GSTGraph  
### Intelligent GST Reconciliation Using Knowledge Graphs  

---

## 📌 Problem Statement  

GST reconciliation in India is complex, fragmented, and prone to ITC leakages due to siloed invoice and return data.

Traditional systems rely on flat table matching.  
GSTGraph redefines reconciliation as a graph traversal problem to detect deep multi-hop mismatches and vendor compliance risks.

---
## 📸 Screenshots 
<img width="1600" height="855" alt="image" src="https://github.com/user-attachments/assets/33965945-086d-4a36-ac77-ca34bf5adf86" />
<img width="1600" height="856" alt="image" src="https://github.com/user-attachments/assets/b59cce28-1ee8-43f7-81f3-84bd5ef120e3" />
<img width="1600" height="852" alt="image" src="https://github.com/user-attachments/assets/8ed4b6f1-3144-4f65-a812-321542e6feaf" />
<img width="1600" height="823" alt="image" src="https://github.com/user-attachments/assets/c6907a1b-6326-41f1-8f1c-d186001de121" />
<img width="1600" height="857" alt="image" src="https://github.com/user-attachments/assets/a181953c-4b97-4af7-8cba-d61eda47fabe" />
<img width="1600" height="840" alt="image" src="https://github.com/user-attachments/assets/81efde11-79f2-4605-ae33-2c7453427f44" />
<img width="1600" height="850" alt="image" src="https://github.com/user-attachments/assets/cf313f5d-f6c5-4475-ac64-1f69654b9c30" />






## 🧠 About GSTGraph  

GSTGraph models India’s GST ecosystem as a Knowledge Graph to enable:

- Multi-hop reconciliation  
- ITC mismatch detection  
- Vendor compliance scoring  
- Financial risk classification  
- Explainable audit trails  

---

## 🚀 Tech Stack  

| Graph Layer | Backend | APIs | Frontend | AI / ML |
|------------|----------|------|-----------|----------|
| Neo4j / Amazon Neptune / ArangoDB | Python (NetworkX) | REST APIs | React Dashboard | Graph ML / Anomaly Detection |

---

## 🏗️ Architecture Overview  

1. GST data ingested as graph nodes & relationships  
2. Invoice → Return → Tax Payment chain validation  
3. Multi-hop traversal mismatch detection  
4. Risk classification engine  
5. Explainable audit output  

---

## ✨ Key Features  

- Knowledge Graph schema for GST ecosystem  
- Multi-hop graph traversal reconciliation engine  
- Root-cause mismatch classification  
- ITC risk prioritization dashboard  
- Vendor compliance scoring  
- Explainable audit output in natural language  
- Predictive compliance risk modeling  

---

## 📊 Core Modules  

### 1️⃣ Knowledge Graph Schema  

Entities:
- Taxpayer  
- GSTIN  
- Invoice  
- IRN  
- GSTR-1 / 2B / 3B  
- Payment Records  

Relationships:
- FILED  
- CLAIMED_ITC  
- GENERATED_IRN  
- MATCHES  
- PAID_TAX  

---

### 2️⃣ Reconciliation Engine  

- Multi-hop traversal validation  
- Invoice-to-payment chain verification  
- Risk-weighted mismatch detection  
- Root-cause classification  

---

### 3️⃣ ITC Risk Dashboard  

- Vendor compliance scores  
- Risk heatmaps  
- High-risk mismatch prioritization  
- Drill-down graph visualization  

---

### 4️⃣ Explainable Audit Trail  

Generates natural-language explanations for:

- ITC denial reasons  
- Missing compliance links  
- Vendor risk classification  

---

## 🔮 Future Improvements  

- Real-time GSTN integration  
- Advanced anomaly detection using Graph ML  
- Network fraud ring detection  
- Scalable distributed graph storage  

---

# 🌐 GSTGraph  
### Making Tax Reconciliation Intelligent, Transparent, and Explainable.
<!--# 🧠 Intelligent GST Reconciliation Using Knowledge Graphs

A FinTech / GovTech solution that models India’s GST ecosystem as a Knowledge Graph to enable multi-hop reconciliation, financial risk classification, and explainable audit trails.

Traditional GST reconciliation relies on flat table matching.  
This system redefines it as a graph traversal problem to detect ITC mismatches, vendor compliance risks, and invoice-to-tax-payment inconsistencies.

---

## 🚀 Tech Stack

- Neo4j / Amazon Neptune / ArangoDB
- NetworkX (Python)
- REST APIs
- React Dashboard
- Graph-based AI/ML models

---

## 🎯 Problem Addressed

India's GST reconciliation impacts over 1.4 crore taxpayers and suffers from ITC leakage due to fragmented data sources.

This system models:

- GSTR-1
- GSTR-2B
- GSTR-3B
- e-Invoices (IRN)
- e-Way Bills
- Purchase Register

as interconnected graph entities instead of flat tables.

---

## 🏗️ Architecture Overview

1. GST data ingested as graph nodes and relationships
2. Multi-hop traversal validates invoice → return → tax payment chains
3. Mismatch classification by financial risk
4. Explainable audit trail generation
5. Vendor compliance risk prediction using graph patterns

---

## ✨ Key Features

- Knowledge Graph schema for GST ecosystem
- Multi-hop graph traversal reconciliation engine
- Root-cause mismatch classification
- ITC risk prioritization dashboard
- Vendor compliance scoring
- Explainable audit output in natural language
- Predictive compliance risk modeling


---

## 📊 Core Modules

### 1️⃣ Knowledge Graph Schema
Entities:
- Taxpayer
- GSTIN
- Invoice
- IRN
- Return (GSTR-1, 2B, 3B)
- Payment Node

Relationships:
- FILED
- CLAIMED_ITC
- GENERATED_IRN
- MATCHES
- PAID_TAX

---

### 2️⃣ Reconciliation Engine

- Multi-hop traversal validation
- Invoice-to-payment chain verification
- Risk-weighted mismatch detection
- Root-cause classification

---

### 3️⃣ ITC Risk Dashboard

- Vendor compliance scores
- Risk heatmaps
- High-risk mismatch prioritization
- Drill-down graph visualization

---

### 4️⃣ Explainable Audit Trail

Natural language output explaining:
- Why ITC was denied
- Missing link in graph chain
- Vendor risk classification

---
## 🔮 Future Improvements

- Real-time GSTN integration
- Advanced anomaly detection using Graph ML
- Network fraud ring detection
- Scalable distributed graph storage

---
--!>
<!--

## 📸 Screenshots

(Add screenshots here – see below for what to include)

## 📌 Note

This project was developed as a collaborative effort.  
This repository reflects my contributions to the system design, backend logic, and dashboard implementation.
This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
--!>
