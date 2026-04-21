# 🧪 Katalon Studio - Saucedemo Test Automation

## 📋 Project Overview

This repository contains automated test cases for **[SauceDemo](https://www.saucedemo.com)** — a demo e-commerce web application — built using **Katalon Studio 11.1.1**.

The project covers functional testing across multiple modules including authentication, inventory sorting, cart management, and checkout flow.

Sit Link : https://docs.google.com/spreadsheets/d/1ie2DqniHcmiwKXiXawpgkUOsNjYV60m_S85qYX29_ZE/edit?usp=sharing

---

## 🛠️ Tech Stack

| Tool | Version |
|------|---------|
| Katalon Studio | 11.1.1 |
| Browser | Chrome / Firefox |
| OS | Mac OS X |
| Language | Groovy |
| Test Site | https://www.saucedemo.com |

---

## 📁 Project Structure

```
katalon-syafiq/
├── Test Cases/
│   ├── Auth/               # Login test cases
│   ├── Checkout/           # Checkout flow test cases
│   ├── Inventory Cart/     # Cart management test cases
│   └── Inventory Sort/     # Sorting test cases
├── Object Repository/
│   ├── Checkout/
│   └── Page_Swag Labs/
├── Test Suites/            # Test suite collections
├── Data Files/
├── Keywords/
└── Reports/
```

---

## 🧾 Test Cases

### 🔐 Authentication (Auth)

| Test Case ID | Test Case Name | Type |
|---|---|---|
| LGN-001 | Login Valid Credential | Positive |
| LGN-002 | Login Locked User | Negative |
| LGN-003 | Login Invalid Username | Negative |
| LGN-004 | Login Invalid Password | Negative |
| LGN-005 | Login Empty Username | Negative |
| LGN-006 | Login Empty Password | Negative |
| LGN-007 | Login Empty Field | Negative |

---

### 🛒 Inventory Cart (ATC)

| Test Case ID | Test Case Name | Type |
|---|---|---|
| ATC-001 | Add Specific Product to Cart (Backpack) | Positive |
| ATC-002 | Add Specific Product to Cart (Bike Light) | Positive |
| ATC-003 | Add Specific Product to Cart (Bolt T-Shirt) | Positive |
| ATC-004 | Add Multiple Products to Cart | Positive |
| ATC-005 | Remove Product from Inventory Page | Positive |

---

### 📊 Inventory Sort (SRT)

| Test Case ID | Test Case Name | Type |
|---|---|---|
| SRT-001 | Sort Product Price (Low to High) | Positive |
| SRT-002 | Sort Product Price (High to Low) | Positive |
| SRT-003 | Sort Product Name (A to Z) | Positive |
| SRT-004 | Sort Product Name (Z to A) | Positive |

---

### 💳 Checkout (CO)

| Test Case ID | Test Case Name | Type |
|---|---|---|
| CO-001 | Complete Checkout Flow - Valid Data | Positive |
| CO-002 | Negative Checkout - Empty First Name | Negative |
| CO-003 | Negative Checkout - Empty Last Name | Negative |
| CO-004 | Negative Checkout - Empty Postal Code | Negative |
| CO-005 | Cancel Checkout on Information Page | Positive |
| CO-006 | Complete Checkout Flow - Valid Data | Positive |
| CO-007 | Navigate Back from Cart to Inventory | Positive |
| CO-008 | Verify Total Price Calculation | Positive |
| CO-009 | Finalize Checkout and Back to Home | Positive |

---

## ▶️ How to Run

### Prerequisites
- Katalon Studio 11.1.1+
- Chrome or Firefox browser
- Git

### Clone Repository
```bash
git clone https://github.com/Syafiqb/katalon-syafiq.git
cd katalon-syafiq
```

### Run Test Cases
1. Open **Katalon Studio**
2. Open project → select folder `katalon-syafiq`
3. Navigate to **Test Cases** or **Test Suites**
4. Right-click → **Run** → select browser

### Run via Test Suite
1. Open **Test Suites** folder
2. Select desired test suite
3. Choose browser from dropdown
4. Click ▶️ **Run**

---

## 🔑 Test Credentials

| Username | Password | Status |
|---|---|---|
| `standard_user` | `secret_sauce` | ✅ Active |
| `locked_out_user` | `secret_sauce` | 🔒 Locked |
| `problem_user` | `secret_sauce` | ⚠️ Problem |

---

## 📊 Test Results Summary

| Module | Total | Passed | Failed |
|---|---|---|---|
| Auth | 7 | - | - |
| Inventory Cart | 5 | - | - |
| Inventory Sort | 4 | - | - |
| Checkout | 9 | - | - |
| **Total** | **25** | - | - |

---

## 👤 Author

**Syafiq Basmallah**  
📧 syafiqbasmallah@gmail.com  
🔗 [GitHub](https://github.com/Syafiqb)

---

## 📄 License

This project is for educational and testing purposes only.
