# Mobile Robot Base – IoT Control Interface

This is a simple Internet of Things (IoT) project to control a mobile robot base using a web interface. It allows sending movement commands and stores each action in a database using PHP and MySQL.

---

## 🔗 Live Demo  
[Click here to open the control interface](https://wael-a-alghamdi.github.io/Mobile-robot-base-internet-of-things-project-2/index.html)

---

## 🔧 Tech Used  
- HTML  
- CSS  
- PHP  
- MySQL  
- Apache or XAMPP (for local testing)

---

## ⚙️ Features  
- Five control buttons: Forward, Left, Right, Stop, Backward  
- Stores each movement in a MySQL table  
- Fetches and displays the last recorded movement  
- Clean, centered web UI using CSS  
- Uses PHP for DB connection and logic

---

## 📝 Notes  
- Requires a local server to run `connect.php` and `select_movement.php`  
- SQL file `mobile_robot_base_project_2_database.sql` creates the required table  
- Background image is referenced as `html_background_image.jpg`  
- This project is for academic/demo use — not for production

---

## 📁 Files  
- `index.html` – Control interface  
- `connect.php` – Saves button input to the database  
- `select_movement.php` – Fetches the last movement value  
- `mobile_robot_base_project_2_database.sql` – SQL schema  
- `html_background_image.jpg` – Background image

---

## 🧾 Project Overview (Arabic + English)

### 1. إنشاء واجهة التحكم – Create (HTML & CSS) Page  
أنشأت صفحة تحكم تتكون من خمسة أزرار: Forward, Left, Right, Stop, Backward، مع تنسيق كامل باستخدام CSS.  
Created a control page with five buttons and styled it using CSS.

---

### 2. إنشاء قاعدة البيانات – Create Database  
قاعدة البيانات تتكون من جدول واحد باسم `movement`، يحتوي على أعمدة تمثل كل حركة بالإضافة إلى معرف `id` كمفتاح أساسي.  
The database contains one table called `movement`, with columns for each movement direction and an `id` as the primary key.

---

### 3. الربط مع قاعدة البيانات – Connect HTML to Database  
استخدمت `connect.php` لربط واجهة التحكم بقاعدة البيانات وتخزين الأوامر المدخلة.  
Used `connect.php` to link the form to the database and store movement commands.

---

### 4. استدعاء آخر حركة – Fetch Last Movement  
أنشأت صفحة `select_movement.php` لاستدعاء آخر قيمة تم إدخالها في قاعدة البيانات وعرضها.  
Created `select_movement.php` to fetch and display the last movement recorded.
