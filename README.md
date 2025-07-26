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

* 🎥 **Demo Video**: [Click to Watch](https://drive.google.com/file/d/1fqPWeCgAw6WjRjGpv-KjUuV46OhrQq0j/view?usp=drive_link)

---

## 🖼️ Custom Objects & Flows Screenshots

### 🔄 Customer Object

*Handsmen Customer*
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/078ea52d-41bc-435e-8650-191187ad192b" />


### 🔄 Order Object

*Handsmen Order*
<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/990f36d4-9ed7-47ff-b3d7-4804de84ff45" />


### 🔄 Product Object

*Handsmen Product*
<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/f11efec6-0349-4f50-9523-833470b15404" />


### 🔄 Inventory Object

*Inventory*
<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/5492bdb8-8a95-4aec-8875-327505a20c0f" />


### 🔄 Marketing Campaign Object

*Marketing Campaign*
<img width="1920" height="1080" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/c162a73e-8d6f-40fc-acd1-d25b2ec34933" />

### ⟲ Classic Email Template

* 🌟 *Loyalty Program Flow*
  <img width="1920" height="1080" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/4d031c54-aca9-41f7-88d7-0e4ba7121a08" />

* 📧 *Order Confirmation Flow*
  <img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/dd42f034-20b6-4373-a698-95df7a1e08fe" />

* 📦 *Stock Alert Flow*
  <img width="1920" height="1080" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/0d4e80bb-ad8c-486b-8367-427b0c5aa4ec" />

  
### ⟲ Key Automation Flows

* 🌟 *Loyalty Program Flow*
 <img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/0b0dc109-d1cd-4d3f-8c49-8320b194a17c" />
 <img width="1920" height="1080" alt="Screenshot (46)" src="https://github.com/user-attachments/assets/647744d6-cf0c-4e5a-a31f-a1204b6ce3ae" />

* 📧 *Order Confirmation Flow*
<img width="1920" height="1080" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/cef465d9-a022-43bb-a728-ae70b7320bf9" />
<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/a8487847-30df-4580-beaf-844b53213be1" />

* 📦 *Stock Alert Flow*
<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/06774a41-fd84-4b85-8179-129b937d9e81" />
<img width="1920" height="1080" alt="Screenshot (49)" src="https://github.com/user-attachments/assets/a15565b3-9889-4f9d-95d9-42af560f312d" />

### 📝 Developer Console

* 💻 *Developer Console Code Snapshots*
<img width="1920" height="1080" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/a3b75363-b227-4f73-a479-adf5978788be" />
<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/e8919ccc-57a3-4998-97fa-978dbeba26af" />
<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/110ec266-7fa7-4546-b9a3-ece7aedcab5c" />
<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/8b7641cb-e1a6-435b-a6a5-ec477d0cdb06" />
<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/190eb29f-d002-49b3-bda6-ce2da2b3d7c8" />
<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/b0ae6470-d459-4dfc-a32c-6268173d596c" />

---

## 📄 License

This project is for **academic and showcase purposes**. Feel free to fork, adapt, or reference for learning.

---

## 💬 Feedback

Have suggestions or want to collaborate?
Open an issue or drop a message — I'd love to connect!


## Commit Changes
If want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for this project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
