# 🏥 Hospital Registration System

## System Analysis & Design Project | 2026


## 1. Project Overview

This project focuses on **analyzing and designing an online hospital appointment registration system** to improve the existing manual registration process at a district-level hospital.

The proposed solution aims to **reduce patient waiting time, improve information handling, support pre-arrival health insurance verification, and enhance the patient registration experience**.

The analysis is based on **138 direct observations conducted over 5 days** at the outpatient reception area of **Nha Be District General Hospital**.


## 2. Business Problem

The current registration process presents several operational challenges:

| Problem | Impact |
|---|---|
| ❌ New patients cannot register online | ~62% of observed patients required registration at the counter |
| ❌ Manual data entry at reception | ~19% of observed cases required information re-entry |
| ❌ Long registration time for new patients | 6m30s average reception time |
| ❌ Health insurance verification at the counter | No pre-arrival validation of information |
| ❌ No upfront cost estimation | Patients do not know expected costs in advance |
| ❌ Patients leaving the queue | 4 cases were observed with waiting time exceeding 25 minutes |

These findings indicate opportunities to improve the registration workflow through **process redesign and system support**.


## 3. Project Objectives

The project aims to:

1. Analyze the current hospital registration process through **138 observations**
2. Identify **6 critical bottlenecks** in the current workflow
3. Design an optimized **TO-BE registration workflow**
4. Define **15 functional and 8 non-functional requirements**
5. Develop system models including **BPC, DFD, ERD, and Relational Data Model**
6. Define **28 business rules (BR01–BR28)**
7. Design **8 key system interfaces**


## 4. My Role

### Business Analyst / System Analyst

| Responsibility | Description |
|---|---|
| 🔍 **Business Process Analysis** | Analyzed the AS-IS registration workflow and identified process bottlenecks |
| 📋 **Requirements Analysis** | Defined functional and non-functional requirements based on identified business needs |
| 🔄 **Process Improvement** | Proposed the TO-BE registration workflow and supporting business rules |
| 📊 **System Modeling** | Developed BPC, DFD, ERD, and relational data models |
| 🖥️ **Interface Design** | Designed 8 key system interfaces |
| 📝 **Documentation** | Prepared system analysis and design documentation |


## 5. Key Deliverables

### 📊 Business Analysis

| Deliverable | Description |
|---|---|
| **BPC** | Business Process Chart covering 5 main functional modules |
| **AS-IS Analysis** | Analysis of the current registration workflow and 6 identified bottlenecks |
| **TO-BE Analysis** | Proposed optimized registration workflow |
| **Functional Requirements** | 15 functional requirements |
| **Non-functional Requirements** | 8 non-functional requirements |
| **Business Rules** | 28 business rules (BR01–BR28) |

### 🏗️ System Analysis & Design

| Deliverable | Description |
|---|---|
| **DFD Context** | System boundary and 6 external entities |
| **DFD Level 0** | 5 main system processes |
| **DFD Level 1** | 5 detailed sub-process diagrams |
| **ERD** | Data model consisting of 7 main entities |
| **Relational Data Model** | 7 relational tables |
| **Entity-Function Matrix** | CRUD mapping between entities and system functions |
| **Interface Design** | 8 key system interface mockups |


## 6. System Scope

| Module | Functions |
|---|---|
| **Patient Management** | Search, receive, and create patient records |
| **Master Data Synchronization** | Synchronize doctors, departments, and schedules from HIS |
| **Appointment Registration** | Register, pay, cancel, change appointments, issue QR codes, and send reminders |
| **Reception & Check-in** | Patient reception, information verification, and HIS synchronization |
| **Monitoring & Reporting** | Dashboard, revenue reports, and department reports |


## 7. Expected Improvements

The proposed TO-BE process is designed to address the issues identified during the AS-IS analysis.

| Metric | AS-IS | TO-BE Target | Expected Improvement |
|---|---:|---:|---:|
| ⏱️ New patient reception time | 6m30s | 2m05s | ↓ 68% |
| ❌ Data entry errors | ~19% | <5% | ↓ ~74% |
| 🔍 Health insurance verification | At counter | Pre-arrival | ✅ Automated |
| 💰 Cost estimation | Not available | Upfront | ✅ New feature |
| 📊 Reporting | Manual | Dashboard-based | ✅ New feature |

> **Note:** TO-BE figures represent proposed targets based on analysis, not results from a production system.


## 8. Technologies & Tools

| Category | Tools / Methods |
|---|---|
| **Business Analysis** | AS-IS / TO-BE Analysis, Requirements Analysis |
| **Process Modeling** | BPC, DFD |
| **Data Modeling** | ERD, Relational Data Model |
| **Interface Design** | Figma |
| **Methodology** | SADT (Structured Analysis and Design Technique) |



## 9. Team & Instructor

| Role | Name |
|---|---|
| **Instructor** | ThS. Dương Thị Hồng Hà |
| **Team Member** | Trần Minh Quốc |
| **Team Member** | Trình Thị Ngọc Nhớ |
| **Team Member** | Trương Thị Thảo Nguyên |
| **Team Member** | Nguyễn Mạnh Trường |
| **University** | Ho Chi Minh City Open University |
| **Faculty** | Information Technology |
| **Academic Year** | 2025–2026 |


## 10. References

1. Hồ Quang Khải (2016). *Tài liệu hướng dẫn học tập Phân tích thiết kế hệ thống thông tin*. Trường Đại học Mở TP.HCM.
2. Hoffer, J. A., George, J. F., & Valacich, J. S. (2016). *Modern Systems Analysis and Design* (8th ed.). Pearson.
3. Laudon, K. C., & Laudon, J. P. (2018). *Management Information Systems* (15th ed.). Pearson.
4. Tilley, S., & Rosenblatt, H. (2016). *Systems Analysis and Design*. Cengage Learning.
5. Elmasri, R., & Navathe, S. B. (2016). *Fundamentals of Database Systems* (7th ed.). Pearson.


