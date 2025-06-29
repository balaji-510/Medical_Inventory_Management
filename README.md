# 🏥 Medical Inventory Management

A Salesforce-based application designed to manage medical stock across healthcare units—tracking products, supplier data, and purchase orders, analytics, and role-specific views.

---

## 📌 Project Overview

This project provides an intuitive and scalable inventory management system tailored for hospitals and clinics. It enables real-time tracking of medicines, automation of purchase workflows, and improved visibility through dashboards—minimizing expiry risks and supply chain delays.

---

## 💡 Features

- ⚙️ **Inventory Lifecycle Management**  
  Track products, expiry dates, and stock levels across departments.

- 📦 **Purchase Order Automation**  
  Generate and approve POs based on low-stock thresholds using Flows and Apex.

- 📈 **Dashboards & Reports**  
  Visualize inventory health, supplier performance, and purchasing trends.

- 👤 **Role-Based Access**  
  Inventory Managers and Purchase Officers see tailored interfaces and permissions.

---

## 🛠️ Tech Stack

| Layer              | Tools Used                       |
|--------------------|----------------------------------|
| Platform           | Salesforce Lightning Experience  |
| Logic & Automation | Apex, Flows, Validation Rules    |
| Data Layer         | Custom Objects & Relationships   |
| Communication      | Email Templates & Approval Flows |
| Visuals            | Reports, Dashboards, DFDs, ERDs  |

---

## 🗂️ Custom Objects

- `Product__c` – Medicine/stock details  
- `Supplier__c` – Vendor contact and ratings  
- `Purchase_Order__c` – Order summary and status  
- `Order_Item__c` – Line-level product records  
- `Inventory_Transaction__c` – Stock movement logs  

---

## 🧪 Setup & Deployment

1. Clone the repository  
2. Import metadata to your Salesforce Developer Org  
3. Configure permission sets and profiles  
4. Load sample data (Products, Suppliers)  
5. Trigger Flows or Apex jobs as needed

> ✅ *Tested in Salesforce Lightning Developer Org*

---

## 📽️ Demo Video

🎬 [Watch the product walkthrough](#)  
(https://drive.google.com/file/d/1wl9Q7XZ6qg6vgHKphBI-30DLMTqUTfAh/view?usp=sharing)

---

## 🔮 Future Scope

- Barcode scanning integration  
- Predictive restock AI using analytics  
- Mobile access for on-floor inventory  
- Digital signature for POs  
- IoT support for temperature-sensitive items
  
---

## 👨‍💻 Contributors

| Name           | Role        | Email                         |
|----------------|-------------|-------------------------------|
| Balaji         | Team Lead   |224G1A0510@srit.ac.in          |
| Bhavitha       | Contributor | 224G1A0511@srit.ac.in         |
| Sree Abhilash  | Contributor | 224G1A05A5@srit.ac.in         |
| Lakshmanji     | Contributor | 224G1A0539@srit.ac.in         |
