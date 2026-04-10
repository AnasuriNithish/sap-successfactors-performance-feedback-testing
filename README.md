# 🏷️ Performance & Feedback Workflow Testing in SAP SuccessFactors

---

## 🎯 Objective
To perform functional and scenario-based testing on employee performance and feedback workflows in SAP SuccessFactors, ensuring proper validation, user interaction, and workflow behavior.

---

## 🧭 Project Overview
This project focuses on testing performance and feedback-related features within SAP SuccessFactors. The testing simulates real-world employee feedback processes and validates system behavior for different input scenarios.

---

## 🔄 Modules Covered

- Performance Management
- Continuous Feedback

---

## 🪜 Step-by-Step Execution

### 🔹 Step 1: Access System
- Logged into SAP SuccessFactors
- Navigated to Home Dashboard

---

### 🔹 Step 2: Open Feedback Module
- Clicked on **"Give Feedback"** option from dashboard
- Verified navigation to feedback form

---

### 🔹 Step 3: Valid Feedback Submission
- Selected employee (e.g., William Anthony Skinner)
- Entered feedback details:
  - What went well
  - Areas of improvement
  - Additional comments
- Clicked **Send**

✅ Result:
- Feedback successfully submitted
- System accepted valid inputs

---

### 🔹 Step 4: Input Validation Testing

#### ❌ Scenario 1: Empty Fields
- Left feedback fields blank
- Attempted submission

✅ Expected:
- System should show validation error

---

#### ❌ Scenario 2: No Employee Selected
- Did not select any employee
- Attempted submission

✅ Expected:
- System should restrict submission

---

### 🔹 Step 5: Duplicate Feedback Scenario
- Attempted to submit feedback again for same user

✅ Expected:
- System should handle duplicate submissions or restrict them

---

### 🔹 Step 6: Notification Validation
- Checked notification icon after feedback submission

✅ Expected:
- System should trigger notification or update status

---

### 🔹 Step 7: Workflow Understanding
Analyzed feedback process:

Employee → Submit Feedback → System Processes → Notification/Status Update

---

## 🧪 Test Scenarios Covered

### ✔️ Positive Scenarios
- Valid feedback submission
- Successful navigation to feedback module

### ❌ Negative Scenarios
- Empty input fields
- Missing employee selection
- Duplicate feedback submission

---

## 🧠 Key Validations Performed

- Input field validation
- Mandatory field checks
- User selection validation
- Workflow triggering behavior
- System response verification

---

## 🛠️ Testing Approach

- Manual Testing
- Functional Testing
- Negative Testing
- Scenario-Based Testing

---

## 📊 Observations

- System successfully accepts valid feedback inputs
- Input validation ensures mandatory fields are filled
- Feedback workflow behaves as expected within trial environment
- Some features may have limited behavior due to trial constraints

---

## 🐞 Defect Summary

No critical defects identified  
Minor limitations observed due to trial system restrictions

---

## 📸 Screenshots

Available in `/screenshots` folder:
- Feedback submission screen
- Validation error scenarios
- Workflow navigation

---
