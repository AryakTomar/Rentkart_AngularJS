# Rentkart – AngularJS Version with Django 

Rentkart is a web-based rental management frontend built using **AngularJS (1.x)**. The project focuses on managing rental-related entities such as categories, customers, products, and user interactions through a simple and modular AngularJS structure.

This repository primarily contains the **frontend implementation** and can be connected to a backend (REST API) for full functionality.

---

## 🚀 Features

* Category management
* Customer management
* Product listing and management
* Modular AngularJS structure
* Bootstrap-based responsive UI
* Simple and beginner-friendly code structure

---

## 🛠️ Tech Stack

* **AngularJS 1.x**
* **HTML5**
* **CSS3**
* **JavaScript (ES5)**
* **Bootstrap**
* **Font Awesome**

---

## 📁 Project Structure

```
Rentkart_AngularJS/
│
├── category/          # Category related views & logic
├── customer/          # Customer related views & logic
├── frontend/          # Main frontend files
├── product/           # Product related components
├── assets/            # CSS, JS, images (if any)
├── index.html         # Entry point of the application
└── README.md          # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AryakTomar/Rentkart_AngularJS.git
```

### 2️⃣ Open the project

You can run this project using any local server.

#### Option A: Using VS Code Live Server

* Install **Live Server** extension
* Right-click on `index.html`
* Select **Open with Live Server**

#### Option B: Using Python

```bash
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

---

## 🔗 Backend Integration

This project can be connected to any backend (Node.js, Django, PHP, etc.) via REST APIs.

Example API usage in AngularJS:

```js
$http.get('http://localhost:8000/api/products')
  .then(function(response) {
    $scope.products = response.data;
  });
```

---

## 📸 Screenshots

*Add screenshots here if available*

---

## 📌 Future Enhancements

* Authentication & Authorization
* Admin dashboard
* Pagination & search
* Improved UI/UX
* Angular upgrade (Angular 16+)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/your-feature-name`)
3. Commit your changes
4. Push to your fork
5. Create a Pull Request

---

## 👤 Author

**Aryak Tomar**
GitHub: [https://github.com/AryakTomar](https://github.com/AryakTomar)

---

If you like this project, ⭐ the repository!
