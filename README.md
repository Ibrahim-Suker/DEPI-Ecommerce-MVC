# 🛒 DEPI Ecommerce MVC

A complete eCommerce web application built using **ASP.NET Core MVC**, following clean architecture principles. This project includes full user and admin functionality, product and category management, and a modern shopping cart experience.

## 📌 Features

- 🛍️ Product browsing by category
- 🧾 Shopping cart functionality
- 👤 User authentication and registration
- 🛡️ Admin panel for managing:
  - Products
  - Categories
  - Orders (optional)
- 📦 Entity Framework Core integration
- 🎨 Clean and responsive UI with Razor Views
- 🔐 Role-based access control (Admin vs. User)
- 📂 Code-First approach with migrations

---

## 🧰 Technologies Used

- **.NET 8 / ASP.NET Core MVC**
- **Entity Framework Core**
- **SQL Server**
- **Razor Pages & Bootstrap**
- **Identity for Authentication & Authorization**
- **LINQ / AutoMapper (if applicable)**

---

## 🚀 Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- Visual Studio 2022 or newer

### Setup Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Ibrahim-Suker/DEPI-Ecommerce-MVC.git
   ```

2. **Navigate to the Project Folder**
   ```bash
   cd DEPI-Ecommerce-MVC
   ```

3. **Update the `appsettings.json` with your SQL Server connection string**

4. **Apply Migrations**
   ```bash
   dotnet ef database update
   ```

5. **Run the Application**
   ```bash
   dotnet run
   ```

---

## 🧪 Future Enhancements

- ✅ Online payment integration (e.g., PayPal or Stripe)
- ✅ Order management dashboard
- ✅ Product image upload and gallery
- ✅ Customer order history

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the project, open issues, or submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

**Ibrahim Suker**  
[GitHub Profile](https://github.com/Ibrahim-Suker)
