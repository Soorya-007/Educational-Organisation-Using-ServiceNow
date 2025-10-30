# 🎓 Educational Organisation – ServiceNow Project

## 📘 Overview
This project is a **ServiceNow application** designed for managing various operations in an educational institution.   
It helps automate the **student admission process**, **track academic progress**, and **store student details** efficiently using the ServiceNow App Engine.

---

## 🧩 Features
- 🔢 **Auto-generated Admin Number** using dynamic defaults  
- 🧑‍🎓 **Student Information Form** for capturing student and parent details  
- 🎯 **Admission Workflow** with multiple statuses:
  - New → In-progress → Joined → Rejected → Closed → Cancelled  
- 📈 **Student Progress Section** to record subject-wise marks, total, percentage, and result  
- 🧱 Built using **ServiceNow App Engine** and **custom tables**

---

## 🖼️ Screenshots

### 1. Admission Form
![Admission Form](Screenshots/Admission_Form.png)

### 2. Admission Process Workflow
![Admission Process](Screenshots/Admission_Process.png)

### 3. Student Progress Form
![Student Progress](Screenshots/Student_Progress.png)

---

## ⚙️ Technical Details
| Component | Description |
|------------|--------------|
| **Platform** | ServiceNow (App Engine Studio) |
| **Type** | Custom Scoped Application |
| **Tables Created** | Admission Form, Admission Process, Student Progress |
| **Automation** | Dynamic Admin Number generation (`Get Next Padded Number`) |
| **UI Elements** | Forms, Choice Lists, and Extensible Controls |
