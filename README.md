# Synthetic SAP APIs – Frugal Innovation Playground

This repo hosts synthetic OpenAPI specifications and a browser-based mock playground
for imagineering and testing SAP integrations without real SAP systems.

## 🌍 Live site
**GitHub Pages:** https://<yourusername>.github.io/synthetic-sap-apis/

## 📘 Available APIs
| API | Description | Raw OpenAPI URL |
|------|--------------|----------------|
| **Business Partner (Synthetic)** | Minimal realistic OpenAPI 3.0 mock of SAP S/4HANA A_BusinessPartner OData API | [View YAML](https://<yourusername>.github.io/synthetic-sap-apis/openapi/business-partner.yaml) |

## 🧩 Playground
Open the in-browser mock app:  
➡️ https://<yourusername>.github.io/synthetic-sap-apis/sap-mock-playground.html

Paste any OpenAPI URL (like the Business Partner YAML) into the input box and click **Load Spec**.

## 🧭 How it works
- All files are static and hosted on **GitHub Pages**
- The mock playground uses **Stoplight Elements** + **JSON Schema Faker** to generate realistic SAP-style data
- No backend or authentication needed — everything runs client-side

## 🪶 Next Steps
- Add new synthetic SAP APIs under `/openapi/`
- Create variations (v1.0, v1.1) to simulate API evolution
- Use the mock responses to prototype Fiori or integration flows
