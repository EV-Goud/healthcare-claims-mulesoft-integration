<div align="center">
  <h1>Healthcare Claims Processing Integration</h1>
  <h3>Batch & Real-time Integration | MuleSoft + Salesforce Service Cloud</h3>

  <img src="https://img.shields.io/badge/MuleSoft-4.2-00A1E0?style=for-the-badge&logo=mulesoft&logoColor=white" alt="MuleSoft" />
  <img src="https://img.shields.io/badge/Salesforce-Service%20Cloud-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce" />
  <img src="https://img.shields.io/badge/HIPAA-Compliant-1E90FF?style=for-the-badge" alt="HIPAA" />

  <p><strong>Processed 20,000+ claims daily</strong> with secure, compliant data handling.</p>
</div>

---

## 📋 Project Overview

Developed robust batch and real-time integration solutions for a leading Healthcare Payer to process and synchronize healthcare claims between internal claims systems and external provider networks using MuleSoft Anypoint Platform.

### Key Achievements
- Designed RESTful APIs following **API-led Connectivity** principles
- Built reusable assets published to **Anypoint Exchange**
- Ensured full **HIPAA-compliant** data handling
- Reduced development redundancy by **40%** through standardization

---

## 🏗️ Architecture

- **API-led Layers**: System, Process, and Experience APIs
- **Integration Patterns**: Real-time + Batch processing
- **Data Formats**: HL7, EDI 837/835 → JSON

**Key Technologies**:
- Mule 4.2
- Salesforce Connector
- JMS & Database Connectors
- DataWeave 2.0
- IBM MQ

---

## ✨ Key Features

- Real-time claims status updates to Salesforce Service Cloud
- HL7 & EDI message transformation with DataWeave
- Asynchronous processing using JMS and Oracle Database
- Reusable connector configurations and libraries
- Comprehensive MUnit testing + integration testing

---

## 📁 Project Structure

```bash
healthcare-claims-integration/
├── src/
│   ├── main/
│   │   ├── mule/
│   │   ├── resources/
│   │   │   ├── api/               # RAML specifications
│   │   │   └── dw/                # DataWeave scripts (HL7/EDI)
│   └── test/
│       └── munit/
├── pom.xml
└── documentation/
    ├── architecture.png
    └── data-mapping.md
