# 🧪 TMS API Testing - Tour Management System

This repository contains API testing work for the **TMS (Tour Management System)** using **Postman**. The project covers testing of various endpoints related to user registration, login, booking tours, and admin operations.

## 📦 About the Project

The TMS platform allows users to:
- Register & manage their profiles
- Book and view tour packages
- Admins to monitor and update bookings

This repo documents the testing of its RESTful APIs using Postman collection.

---

## 📂 Folder Structure

```
TMS-API-Testing/
├── TMS_API_Collection.postman_collection.json
├── screenshots/              # (optional) Add screenshots of responses
└── README.md
```

---

## 🔑 Key Features Tested

### 👤 User APIs
- `POST /registration.php` – Register a new user
- `POST /login.php` – Login with credentials
- `POST /fetch-user.php` – Fetch account details via token
- `PUT /update.php` – Update user profile
- `DELETE /delete.php` – Delete user account

### 🧳 Booking APIs
- `POST /booktour.php` – Book a tour package
- `POST /checkbookings.php` – View bookings via email
- `POST /deletebooking.php` – Cancel a booking

### 🛠 Admin APIs
- `GET /admin/getallusers.php` – View all users
- `GET /admin/getallbookings.php` – View all bookings
- `PUT /admin/updatestatus.php` – Update booking status
- `POST /admin/bookingstatus.php` – Filter bookings by status

---

## ⚙️ Tools Used
- [Postman](https://www.postman.com/) – API testing
- JSON – Payload formatting
- REST API – HTTP Methods: GET, POST, PUT, DELETE

---

## 🚀 How to Use

1. Import the collection into Postman
2. Use raw JSON payloads for testing (included in each request)
3. Replace tokens as needed with active session data
4. Check status codes, response messages, and data accuracy

---

## ✅ Outcome

- Validated 13+ endpoints for both user and admin functionality
- Tested input validation, response formats, and error handling
- Ensured token-based secure access for user operations

---

## 👨‍💻 Author

**Kartik Bhatt**  
🔗 [LinkedIn](https://www.linkedin.com/in/kartik-bhatt-68b534226/)  
📧 bhattkartik553@gmail.com

---

> This project was created as part of my software testing work and helps demonstrate API validation and documentation skills.
