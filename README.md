# Login Use Case – UC-02

## 📌 Project Overview
This project documents the **Login Use Case** for an online system. It describes how a registered online user logs into the system and accesses their account summary page.


---

## 🧾 Use Case Details

| Field | Description |
|------|-------------|
| **Use Case Name** | Login |
| **Use Case ID** | UC-02 |
| **Primary Actor** | Registered Online User |
| **Trigger** | User enters User ID |
| **Pre-Conditions** | 1. User must be a registered online user  <br> 2. User account must be active (not locked) |
| **Post-Condition** | User is able to view the Account Summary page |

---

## 📖 Use Case Story
This use case enables a registered online user to log into the system and access their account online.

---

## 🔄 Primary Flow (PF)
**Title:** User is able to log in without any errors

| Step | Actor Action | System Response |
|------|-------------|-----------------|
| 1 | User enters User ID | |
| 2 | User clicks **Continue** button | 3. System validates User ID <br> • If valid → proceed <br> • If invalid → go to AF1 |
| | | 4. System displays Password page |
| 5 | User enters Password | |
| 6 | User clicks **Login** button | 7. System validates Password <br> • If valid → proceed <br> • If invalid → go to AF2 |
| | | 8. System displays Account Summary page |

---

## ⚠️ Alternate Flows

### 🔁 AF1 – Invalid User ID
- System displays error message: **"Invalid User ID"**
- User is prompted to re-enter User ID

### 🔁 AF2 – Invalid Password
- System displays error message: **"Incorrect Password"**
- User is prompted to re-enter Password

---

## 🛠️ Project Context
- Requirements Analysis
- Use Case Modeling
- System Analysis
- Business Analysis Documentation

---

## 📂 Possible Enhancements
- UML Use Case Diagram
- Sequence Diagram
- UI Wireframes
- Additional Use Cases:
  - Register
  - Forgot Password
  - Logout

---

## 👤 Author
**Saad Elboukhali**

---

## ⭐ Notes
This project can be extended into a full system requirements specification by adding more use cases and diagrams.
