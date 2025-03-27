# Rapid Response - Cab Booking Website

## 🚀 Overview
Rapid Response is a **cab booking web application** designed to provide a seamless and efficient ride-booking experience. Users can **select car types, track locations in real-time**, and get **instant fare estimations**. The platform ensures a **secure and user-friendly** booking process.

## 🔧 Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP, MySQL
- **APIs:** MapIndia API for real-time location tracking

## 🎯 Features
- 🗺 **Real-time Location Tracking**: Uses the **MapIndia API** to track users and available cabs.
- 🔐 **Secure Authentication**: Users can sign up, log in, and manage their ride history.
- 🚕 **Cab Selection**: Choose from different vehicle types based on comfort and budget.
- 💰 **Dynamic Fare Estimation**: Get real-time fare estimates before booking a ride.
- 📜 **Ride History**: View past bookings and trip details.

## 📂 Project Structure
```
Rapid-Response/
│── index.php          # Homepage with booking form
│── login.php          # User authentication page
│── register.php       # New user registration
│── dashboard.php      # User dashboard for ride history
│── book-ride.php      # Ride booking logic
│── api/
│   ├── mapAPI.php     # Integration with MapIndia API
│   ├── fareCalc.php   # Dynamic fare calculation logic
│── assets/
│   ├── styles.css     # Custom CSS styles
│   ├── scripts.js     # JavaScript for UI interactions
│── database/
│   ├── db_connect.php # Database connection script
│   ├── schema.sql     # Database schema
└── README.md          # Project documentation
```

## 🛠 Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/isatyam05102003/rapid-response.git
   ```
2. Set up the database:
   - Import the `schema.sql` file into MySQL.
   - Configure database credentials in `db_connect.php`.
3. Start the local server:
   - Use **XAMPP** or **WAMP** to run the project.
4. Open `index.php` in the browser to start booking cabs!

## 🤝 Contributing
Feel free to **fork** this project, open **issues**, and submit **pull requests**. Contributions are welcome!

## 📜 License
This project is **open-source** and available under the **MIT License**.
