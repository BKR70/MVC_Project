# Property Management System 🚀
The Property Management System is a web platform for buying or renting properties. It offers features like property search by city and zone, filtering, booking, and payment integration. 

## 📌 Features

### 🏘️ Property Search & Listings
- Browse properties available for **buying** or **renting**.
- Search properties by **city**, **zone**, or **location**.
- View detailed property information with images, price, and features.

### 🔍 Smart Filtering
- Filter properties by:
  - Property type (house, flat, land, etc.)
  - Price range
  - Number of bedrooms/bathrooms
  - Rent or sale availability

### 📅 Booking System
- Book a property for rent or viewing.
- See property availability in real time.
- Manage booking history from the user dashboard.

### 💳 Payment Integration
- Online payment support for property booking or rental fees.
- Secure transaction handling via integrated payment gateway.

### 👤 User Authentication & Roles
- Separate user roles: **Admin**, **Seller/Owner**, **Customer/Buyer**.
- Admin can manage all listings, users, and bookings.
- Sellers can list and manage their own properties.
- Buyers can search, book, and make payments.

### 📊 Admin Dashboard
- Approve or reject listed properties.
- Manage bookings and payments.

## ⚡ Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/BKR70/MVC_Project.git
   cd MVC_Project
   
2. **Open the project in Visual Studio**
   - Open PropertyManagementSystem.sln
    
3. **Set up the database**
   - Edit `appsettings.json` with your SQL Server connection string.
   - Run the following in **Package Manager Console**:
     ```bash
     Add-Migration InitialCreate
     Update-Database
     ```
   - This will apply Entity Framework migrations and create the required database schema.
     
4. **Run the application**
   - click the **Start** button in Visual Studio.

5. 🛠️ Technologies Used
   - ASP.NET Core MVC 
   - Entity Framework Core
   - MS SQL Server
     
