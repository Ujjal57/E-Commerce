# 🛒 Shop Nix – Electronics eCommerce Website

A full-featured electronics eCommerce website built using **HTML, CSS, JavaScript, PHP, and MySQL**. It supports both **user** and **admin login**, showcases products by category, allows cart and wishlist management, and features a clean, animated UI inspired by Netflix’s intro style.

## 🚀 Features


- 🔐 **User & Admin Login/Register**
- 🛍️ **Shop by Categories** – Laptop, Smartphone, Camera, and Watch
- ❤️ **Wishlist & Cart Functionality**
- 🛒 **Product Purchase and Order Simulation**
- 📦 **Admin Dashboard for Product Management**
- 📜 **Order History and Management**
- 📱 **Responsive Design using Flexbox and Swiper.js**

---

## 📂 Project Structure

```
📁 E-Commerce
│── admin/
│   ├── admin_accounts.php   # Pickle file containing movie data
│   ├── admin_login.php       # Precomputed similarity matrix
│   ├── dashboard.php           # Movie dataset
│   ├── messages.php
│   ├── placed_orders.php
│   ├── products.php
│   ├── register_admin.php
│   ├── update_product.php
│   ├── update_profile.php
│   ├── users_accounts.php        # Movie credits dataset
|── components/
│   ├── admin_header.php
│   ├── admin_logout.php
│   ├── connect.php
│   ├── footer.php
│   ├── user_header.php
│   ├── user_logout.php
│   ├── wishlist_cart.php            # CSS for frontend styling
|── css/
|   ├── admin_style.css
|   ├── style.css            # HTML template for the homepage
│── images                    # Main Streamlit application
│── js
│   ├── admin_script.js
│   ├── script.js         # Python dependencies
│── uploaded_img
│── README.md              # Project documentation
├── about.php
├── cart.php
├── category.php
├── checkout.php
├── contact.php
├── home.php
├── orders.php
├── quick_view.php
├── search_page.php
├── shop.php
├── shop_db.sql
├── update_user.php
├── user_login.php
├── user_register.php
├── wishlist.php 
```

---

## ⚙️ Installation

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/Ujjal57/E-Commerce.git
cd E-Commerce
```

### 🔹 2. Set Up XAMPP

- Install [XAMPP]
- Start **Apache** and **MySQL** services
- Copy the project folder to:

```makefile
C:\xampp\htdocs\projectdone
```

### 🔹 3. Create and Import Database

- Go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Create a new database: `shop_db`
- Import `shop_db.sql` file into the new database

### 🔹 4. Run the Website

Open in your browser:

```arduino
http://localhost/projectdone
```

---

## 🛠️ How It Works

- **User Registration & Login** – Users and Admins can securely sign in.
- **Intro Animation** – A one-time animated "Shop Nix" text overlay on load.
- **Browse Products** – Products shown by category with hover animations.
- **Wishlist & Cart** – Add products to your cart or wishlist.
- **Order Placement** – Simulate buying items (no real payment processing).
- **Admin Dashboard** – Admin can add/edit/delete products and view orders.

---

## 🖼️ Screenshots

> (Add your screenshots in the `screenshots/` folder and embed them like below)

```
| ![Intro](screenshots/intro.gif) | ![Home](screenshots/home.png) | ![Cart](screenshots/cart.png) |
```

---

## 🔐 Admin Panel Access

You can log in as admin using:

```makefile
Username: Ujjal
Password: Ujjal
```

⚠️ Ensure these credentials exist in your database or insert them manually using phpMyAdmin.

---

## 🔮 Future Enhancements

- ✅ Add real payment gateway (Razorpay/Stripe)
- ✅ Add product ratings and reviews
- ✅ Implement search bar with filters
- ✅ Enable product quantity stock control
- ✅ Add delivery tracking simulation
- ✅ Responsive PWA support for mobile view

---

## 👨‍💻 Developer

**Ujjal** – *Full Stack Developer*
