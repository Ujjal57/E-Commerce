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

### 🔹 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv env
source env/bin/activate   # On macOS/Linux
env\Scripts\activate      # On Windows
```

### 🔹 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 🔹 4. Run the notebook86c26b4f17.ipynb file

Place `movie_list.pkl` and `similarity.pkl` inside the `model/` directory.

### 🔹 5. Run the Application

```bash
python -m streamlit run app.py
```

---

## 🛠️ How It Works

1. **Data Loading**: The system loads movie data (`movies.csv`, `credits.csv`).
2. **Preprocessing**: Extracts genres and prepares data for recommendations.
3. **Machine Learning Model**: Uses a precomputed similarity matrix (`similarity.pkl`).
4. **Movie Recommendation**: Finds similar movies based on cosine similarity.
5. **Poster & Trailer Fetching**: Calls TMDB API to get movie details.
6. **Streamlit UI**: Provides an interactive web-based interface.

---

## 🖼️ Screenshots


| ![Loading](1.png) | ![Home Screen](2.png) | ![Recommendations](3.png) |


## 🔑 API Usage

This project uses [TMDB API](https://www.themoviedb.org/documentation/api) to fetch movie details.

- To use this API, get an API key from TMDB.
- Replace `TMDB_API_KEY` in `app.py` with your own key.

```python
TMDB_API_KEY = "your_tmdb_api_key_here"
```

---

## 🔮 Future Enhancements

- ✅ Add personalized recommendations based on user history.
- ✅ Improve UI/UX with better styling and animations.
- ✅ Implement user authentication (Firebase) for a personalized experience.

---

## 👨‍💻 Contributors

- **Ujjal** - *Developer*

---
