
---

# 🚀 DigitalKhaata - E-Commerce Admin Portal

**DigitalKhaata** is a lightweight, responsive, single-page E-Commerce Admin Dashboard built using **HTML5, CSS3, JavaScript (ES6+), Bootstrap 5, FontAwesome, and Chart.js**. It provides store administrators with an intuitive interface to monitor live store metrics, manage product inventory, track customer orders, and update profile settings—all without external backend dependencies.

---

## ✨ Features

* **📊 Live Interconnected Analytics Dashboard**
* Real-time KPI summaries: Total Revenue, Total Orders, Active Products, and Pending Shipments.
* Interactive **Sales Revenue Statistics** line chart and **Category Stock Distribution** doughnut chart powered by **Chart.js**.
* Dynamically updates metrics whenever orders or product stocks are modified.


* **📦 Products & Inventory Management**
* **Visual Gallery View:** Grid layout displaying product items with category filter buttons (*All, Electronics, Accessories, Apparel*).
* **Quick Edit Inventory Table:** Allows inline editing of product prices and stock quantities.
* **Add & Delete Products:** Modal form to seamlessly add new inventory items with automatic SKU generation.


* **🛒 Order Management System**
* Tabular list of customer orders with real-time status badges (*Pending, Processing, Shipped, Delivered*).
* Interactive dropdown menu to instantly change order status, recalculating live revenue and pending order counts on the main dashboard.


* **👤 Profile & Account Management**
* Store Administrator profile section with editable details (Name, Email, Phone Number).
* Synchronized profile updates across top navbar user chips and account header views.


* **📱 Fully Responsive & Mobile Friendly**
* Custom slide-in navigation sidebar with an overlay backdrop on screens smaller than 768px.
* Modern, clean UI built on Google's *Poppins* typography and a custom color palette.



---

## 🛠️ Tech Stack & Dependencies

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla ES6)
* **CSS Framework:** [Bootstrap 5.3.0](https://getbootstrap.com/)
* **Icon Library:** [FontAwesome 6.4.0](https://fontawesome.com/)
* **Typography:** [Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins)

---

## 📁 Project Structure

```text
DigitalKhaata/
│
└── index.html       # Single-page complete source file (HTML, CSS, & JS)

```

---



### Running the Application

1. Download or clone this repository.
2. Open `index.html` directly in any web browser (Chrome, Firefox, Edge, Safari).

---

## 📖 Usage Guide

1. **Navigating the App:** Use the left sidebar to switch between **Dashboard**, **Products & Inventory**, **Orders**, and **My Account**.
2. **Adding a Product:** Go to *Products & Inventory* $\rightarrow$ Click **"Add Product"** $\rightarrow$ Fill out the details in the modal $\rightarrow$ Submit.
3. **Editing Inventory Inline:** Click directly on any price or stock value inside the *Inventory Quick Edit Table* to open an inline prompt editor.
4. **Updating Order Status:** Go to *Orders* $\rightarrow$ Select a new status from the dropdown menu for any order. Notice how the *Total Revenue* and *Pending Shipments* metrics auto-update on the *Dashboard*.

---

