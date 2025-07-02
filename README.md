# Food Delivery System

This is a food delivery management system designed to handle customers, inventory, and orders. It includes secure login, role-based access, and database integration with MySQL — all built using **Spring Boot** and **Thymeleaf**.

> 🔗 GitHub Repo: [VihaShahh/Food\_delivery\_system](https://github.com/VihaShahh/Food_delivery_system)

---

## ✅ Key Features

* 👤 **Customer Management** – Add, update, and delete customers
* 📦 **Inventory Tracking** – Manage food items, prices, and stock
* 🧾 **Order Management** – Create and manage customer orders
* 🔐 **Login & Authentication** – Secure login for admins/staff
* 👥 **Role-Based Access** – Different views & access for admin/staff
* 🖼️ **Thymeleaf Templates** – Dynamic HTML pages
* 🗄️ **MySQL Integration** – Real-time database connectivity

---

## 🛠️ Tech Stack

| Layer    | Technology                           |
| -------- | ------------------------------------ |
| Backend  | Java 8, Spring Boot, Spring MVC, JPA |
| Frontend | Thymeleaf, HTML, CSS, JavaScript     |
| Database | MySQL                                |
| Tools    | Eclipse / Spring Tool Suite, Maven   |

---

## 🚀 How to Run

### Prerequisites:

* Java 8
* MySQL
* Maven
* IDE like Eclipse or Spring Tool Suite (STS)

### Setup Steps:

1. **Clone the repo:**

   ```bash
   git clone https://github.com/VihaShahh/Food_delivery_system.git
   cd Food_delivery_system
   ```

2. **Configure Database:**

   * Create a database in MySQL (e.g., `food_delivery_db`)
   * Update the `application.properties` file with your DB username, password, and DB name:

     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/food_delivery_db
     spring.datasource.username=your_mysql_username
     spring.datasource.password=your_mysql_password
     ```

3. **Run the project:**

   ```bash
   mvn spring-boot:run
   ```

4. **Open in Browser:**

   ```
   http://localhost:8080
   ```

---

## 🗂️ Project Structure

```
Food_delivery_system/
├── src/
│   ├── main/
│   │   ├── java/com/example/
│   │   │   ├── controller/       # Request handlers
│   │   │   ├── model/            # Entity classes
│   │   │   ├── repository/       # JPA Repositories
│   │   │   └── service/          # Business logic
│   │   └── resources/
│   │       ├── templates/        # Thymeleaf views
│   │       ├── static/           # CSS / JS files
│   │       └── application.properties
└── pom.xml                       # Maven config
```

---

**Viha Shah**
📍 India
🔗 [LinkedIn](https://www.linkedin.com/in/vihashahh)

---

