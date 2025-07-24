# 🧵 HandsMen Threads - Salesforce Project

Elevating the Art of Sophistication in Men's Fashion

---

This project represents a **Salesforce-based digital transformation** initiative for HandsMen Threads, a forward-thinking fashion brand. The goal is to streamline internal operations and enhance customer engagement through intelligent automation, robust data models, and personalized user experiences.

---

## 📂 Table of Contents

* [🚀 Project Overview](#-project-overview)
* [🛠️ Key Features](#️-key-features)
* [📊 Data Model Highlights](#-data-model-highlights)
* [⚙️ Technologies & Tools Used](#️-technologies--tools-used)
* [📚 What I Learned](#-what-i-learned)
* [🔗 Project Links](#-project-links)
* [🖼️ Custom Objects & Flows Screenshots](#-custom-objects--flows-screenshots)
* [📄 License](#-license)
* [💬 Feedback](#-feedback)

---

## 🚀 Project Overview

HandsMen Threads is implementing Salesforce to **centralize data**, **automate workflows**, and boost **operational efficiency**. The application is designed for use by sales, customer service, and inventory teams to ensure seamless communication and real-time insights across departments.

---

## 🛠️ Key Features

* ✅ **Automated Order Confirmations**
  Customers receive email confirmations instantly after placing an order.

* 🏆 **Dynamic Loyalty Program**
  Loyalty tiers update automatically based on customer purchase history.

* 📦 **Proactive Stock Alerts**
  Inventory team receives alerts when stock falls below 5 units.

* 🕛 **Scheduled Bulk Order Updates**
  Nightly batch jobs update financial records and inventory data.

---

## 📊 Data Model Highlights

### 🔹 Custom Objects

* **Customer**
* **Order**
* **Product**
* **LoyaltyTier**
* **Inventory**

### 🔗 Relationships

* One-to-Many: `Customer → Order`
* Many-to-One: `Order → Product`
* One-to-One: `Customer → LoyaltyTier`

---

## ⚙️ Technologies & Tools Used

| Tool                     | Purpose                                |
| ------------------------ | -------------------------------------- |
| Salesforce Lightning App | Custom UI and layout creation          |
| Record-Triggered Flows   | Automate real-time operations          |
| Apex Triggers            | Update loyalty status & business logic |
| Batch Apex               | Handle bulk processing of records      |
| Validation Rules         | Maintain data integrity                |
| Scheduled Apex           | Run nightly batch jobs                 |

---

## 📚 What I Learned

* Designing **scalable Salesforce data models**
* Automating processes using **Flows and Apex**
* Maintaining **data quality** with validation and error handling
* Building apps with **Lightning App Builder**
* Writing both **synchronous and asynchronous Apex logic**

---

## 🔗 Project Links

* 🎥 **Demo Video**: [Click to Watch]()
* 💻 **GitHub Repository**: [HandsMen Threads Salesforce]()

---

## 🖼️ Custom Objects & Flows Screenshots

### 🔄 Customer Object

*Customer*
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/078ea52d-41bc-435e-8650-191187ad192b" />


### 🔄 Order Object

*Order*
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/990f36d4-9ed7-47ff-b3d7-4804de84ff45" />


### 🔄 Product Object

*Product*
<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/f11efec6-0349-4f50-9523-833470b15404" />


### 🔄 Inventory Object

*Inventory*
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/5492bdb8-8a95-4aec-8875-327505a20c0f" />


### 🔄 Marketing Campaign Object

*Marketing*

### ⟲ Key Automation Flows

* 🌟 *Loyalty Program Flow*
* 📧 *Order Confirmation Flow*
* 📦 *Stock Alert Flow*

### 📝 Templates & Developer Console

* 📨 *Classic Email Template*
* 💻 *Developer Console Code Snapshots*

---

## 📄 License

This project is for **academic and showcase purposes**. Feel free to fork, adapt, or reference for learning.

---

## 💬 Feedback

Have suggestions or want to collaborate?
Open an issue or drop a message — I'd love to connect!
# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

## How Do You Plan to Deploy Your Changes?

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
