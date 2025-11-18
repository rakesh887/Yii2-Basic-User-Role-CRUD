# Yii2 Assignment – User & Project Management System  
**Author:** Rakesh Kumar
**Framework:** Yii2 Basic Template 
---

-----------Login Access----------------
E-Mail : test@gmail.com
Password : 123456
========================================

# Project Description
This project is built using **Yii2 Basic Template**, implementing:

- User Management (Signup, Login, Role-based Access)
- Admin, Manager & User Roles
- Project Management (CRUD)
- Role-based Dashboard
- MVC Structure
- Yii2 Access Control Filter (ACF)
- Migrations for database tables

---

# Complete Project Structure (ALL FILES LISTED)

## controllers/
### **1. DashboardController.php**
- User Count  
- Project Count  
- Logout
http://localhost/yii2/toxsl/web/index.php?r=dashboard%2Findex

### **2. ProjectController.php**
- Index (List Projects)  
- Create Project  
- Update Project  
- View Project  
- Delete Project
http://localhost/yii2/toxsl/web/index.php?r=project%2Findex 

### **3. UserController.php**
- Index (List Projects)  
- Create Project  
- Update Project  
- View Project
- Delete Project
http://localhost/yii2/toxsl/web/index.php?r=user%2Findex

### **4. UserRoleController.php**
- Index (List Projects)  
- Create Project  
- Update Project  
- View Project  
- Delete Project
http://localhost/yii2/toxsl/web/index.php?r=userrole%2Findex

---

## models/

### **1. User.php**
- User identity class
- Password hashing
- Role property

### **2. Login.php**
- Login validation
- Authentication rules  

### **3. User.php**
- Signup validation
- Create new user

### **4. Project.php**
- Project model

### **5. SignupController.php**
http://localhost/yii2/toxsl/web/index.php?r=signup/index

### **6. LoginController.php**
http://localhost/yii2/toxsl/web/index.php?r=login/index

## 1. Site Views
1.1 views/login/index.php

User login page
Fields: Email, Password
Validates user credentials
Successful login → Redirects to Dashboard

1.2 views/dashboard/index.php
Features:
Welcome message
Logged-in user AND role

## 2. User Management Views
2.1 views/user/index.php
User listing page
Columns: Name, Email, Telephone, Role, Status, Action buttons
Edit / Delete options

2.2 views/user/_form.php

User create/update form.

Key features:
Name
Email
Telephone
Password (if password blank to old password)
Role (Dropdown)
Status (Enabled/Disabled)
Full client-side validation

## 3. User Roles Views
3.1 views/userrole/index.php

Displays list of roles
Add / Update links
Columns:
Role name
Access Permission
Modify Permission

3.2 views/userrole/form.php
Form for adding/updating roles
Fields:
Role name
Access Permission
Modify Permission

## 4. Project Views
4.1 views/project/index.php

Displays list of projects
Add / Update links
Columns:
Project name
Description
Status

4.2 views/project/form.php
Form for adding/updating project
Fields:
project name
Description
Status

DataBase Name: toxsl_yii2basic
