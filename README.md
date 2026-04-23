# 📘 Faculty Trigger Lab – MySQL Project

##  Overview
This project demonstrates MySQL triggers to automatically update employee salaries based on job duration and number of publications. It also logs all salary changes.

---

##  Database
faculty_trigger_lab

---

##  Tables

### EMPLOYEE
Stores employee data including salary and publication info.

### SALARY_LOG
Stores history of salary updates (old salary, new salary, time, note).

---

## ⚙️ Salary Rules
- 20% → >1 year & publications > 4  
- 10% → >1 year & publications 2–3  
- 5% → >1 year & publications = 1  
- 0% → otherwise  

---

##  Triggers
- BEFORE UPDATE: Calculates IncrementRate & UpdatedSalary  
- AFTER UPDATE: Stores changes in SALARY_LOG  

---

##  Testing
Updated 4 employees to test all conditions and verified results.

---

##  Run
1. Create database and tables  
2. Insert data  
3. Create triggers  
4. Run UPDATE queries  
5. Check EMPLOYEE and SALARY_LOG tables  

---

## 🎯 Outcome
Learned MySQL triggers, automation, and database logging system.

