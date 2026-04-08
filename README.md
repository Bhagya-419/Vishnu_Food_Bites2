# Vishnu Food Bites 🍴

A simple and user-friendly **Food Ordering Website** designed for college canteens/hostels, where students can browse menus, place orders, and track their food in real-time.
This project focuses on **clean design, easy navigation, and efficient backend integration**.

---

## 🚀 Features

* 📋 **Menu Display** – View available food items with prices and categories.
* 🛒 **Add to Cart** – Add items to cart and review before confirming.
* 🔑 **Authentication** – User login/signup with PHP and MYSQL.
* 💳 **Order Placement** – Place orders and get confirmation.
* 📊 **Order History** – Check previous orders.
* 🔔 **Notifications** – Real-time status updates of orders.

---

## 🛠️ Tech Stack

**Frontend**

* HTML5, CSS3, JavaScript
* Responsive design

**Backend & Database**

* PHP
* MySQL (XAMPP or phpMyAdmin)

---

VISHNU_FOOD_BITES2/
│
└── vishnu_food_bites2/
    │
    ├── images/
    │   ├── brownie.webp
    │   ├── cakes.webp
    │   ├── carrotjuice.jpeg
    │   ├── centralsquare.jpg
    │   ├── chickenburger.webp
    │   ├── chickenpoppers.webp
    │   ├── chickenpuffs.jpg
    │   ├── chickenwings.webp
    │   ├── chocolates.jpeg
    │   ├── coffee.jpeg
    │   ├── cooldrinks.jpg
    │   ├── frenchfries.webp
    │   ├── grapejuice.jpg
    │   ├── icecreams.webp
    │   ├── juicydrinks.jpg
    │   ├── karbhujajuice.jpg
    │   ├── lays_kurkure.webp
    │   ├── milkshakes.jpg
    │   ├── orangejuice.webp
    │   ├── pomegranatejuice.webp
    │   ├── rolls.jpg
    │   ├── sandwich.webp
    │   ├── templesquare.jpg
    │   ├── vegballs.avif
    │   ├── vegpuffs.jpg
    │   ├── vegsticks.jpg
    │   ├── watermelonjuice.jpg
    │   └── yummie.jpg
    │
    ├── sql/
    │   └── vishnu_food_bites.sql
    │
    ├── a1.php
    ├── accept_order.php
    ├── addtocart.php
    ├── admin1.php
    ├── adminfood1.php
    ├── adminfood2.php
    ├── adminfood3.php
    ├── adminfood4.php
    ├── cart.php
    ├── check_stock.php
    ├── db_config.php
    ├── fooditems1.php
    ├── fooditems2.php
    ├── fooditems3.php
    ├── fooditems4.php
    ├── get_cart.php
    ├── homepage.php
    ├── index.php
    ├── logout.php
    ├── orderplaced.php
    ├── process_accept_order.php
    ├── removefromcart.php
    ├── save_orders.php
    ├── signup.php
    ├── u2.php
    ├── update_quantity.php
    ├── users_ordered_items.php
    └── view_orders.php


---

## ⚙️ Setup & Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Bhagya-419/VishnuFoodBites.git
   cd VishnuFoodBites
   ```

2. Open the project in your editor (VS Code recommended).

---

3. Setup Instructions

1. **Install XAMPP** and start **Apache** and **MySQL** from the control panel.
2. Open **phpMyAdmin** → create a database named **`vishnu_food_bites`**.
3. Import the file **`vishnu_food_bites.sql`** into the database.
4. Copy the project folder **`VISHNU-FOOD-BITES`** into the `htdocs` directory:

   ```
   C:\xampp\htdocs\VISHNU-FOOD-BITES\
   ```
5. Check the **`db_config.php`** file and ensure it matches:

   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $database = "vishnu_food_bites";
   ```
6. Open your browser and run the project at:

   ```
   http://localhost/VISHNU-FOOD-BITES/
   ```
   
---

🎥 **Project Demo Video:**  
[Click here to watch the demo](https://github.com/user-attachments/assets/f3b83994-fe49-4b9a-b17c-f98ffa8b641c)

---

## 👩‍💻 Contributors
- Bhagya 
- Pavani  
- Pranathi  
- Pravalika  
- Rajasri

---

## 📜 License

This project is licensed under the MIT License – feel free to use and modify it for learning purposes.

---



📝 **Note:**  
Each PHP file includes its own HTML, CSS, and JavaScript code.  
The project starts from `index.php`.
