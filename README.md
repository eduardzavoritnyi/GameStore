# 🎮 Game Store – WordPress WooCommerce (Docker)

Game Store is a modern eCommerce website built with WordPress and WooCommerce for selling digital and physical games.
The project is fully containerized using Docker for fast and easy deployment.

---

## 🚀 Features

* 🛒 WooCommerce integration
* 🎮 Game catalog with categories & filters
* 🔍 Search functionality
* 👤 User authentication
* 💳 Payment system support
* 📦 Order management
* 📱 Responsive design
* ⚡ Optimized performance
* 🐳 Docker-based environment

---

## 🛠️ Tech Stack

* WordPress (CMS)
* WooCommerce (plugin)
* PHP
* MySQL
* Docker & Docker Compose
* HTML / CSS / JavaScript

---

## 📦 Docker Setup

### 🔧 Requirements

* Docker
* Docker Compose

---

### ▶️ Installation & Run

1. Clone repository:

```bash
git clone https://github.com/your-username/game-store.git
cd game-store
```

2. Create `.env` file (optional):

```env
MYSQL_ROOT_PASSWORD=root
MYSQL_DATABASE=gamestore
MYSQL_USER=wordpress
MYSQL_PASSWORD=wordpress
```

3. Run containers:

```bash
docker-compose up -d
```

4. Open in browser:

```
http://localhost:8000
```

---

## 🐳 Services

* **wordpress** – WordPress application
* **mysql** – MySQL database
* **phpmyadmin** *(optional)* – database management

---

## ⚙️ Useful Commands

```bash
# Stop containers
docker-compose down

# Rebuild containers
docker-compose up -d --build

# View logs
docker-compose logs -f
```

---

## 📁 Project Structure

```
.
├── docker-compose.yml
├── .env
├── wp-content/
│   ├── themes/
│   │   └── game-store-theme/
│   └── plugins/
```

---

## 🧩 Plugins

* WooCommerce
* 

---

## 🎨 Theme

Custom WordPress theme developed specifically for Game Store.

---

## 📸 Screenshots

<img src="https://res.cloudinary.com/dy2v6wyku/image/upload/v1774968777/Screenshot_1_dq9xea.png" alt="Game Store" width="500" height="600">
---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

https://www.linkedin.com/in/edzavoritnyi/?locale=uk_UA
