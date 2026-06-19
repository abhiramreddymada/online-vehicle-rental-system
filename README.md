# 🚗 Online Vehicle Rental System

A frontend web application that allows users to browse, select, and rent vehicles online with a complete authentication system.

---

## 💡 About the Project

Online Vehicle Rental System is a web-based platform that simplifies the vehicle rental process. Users can register, browse available vehicles, add them to cart, and complete their booking — all from one place!

---

## ⚙️ Tech Stack

| Technology | Usage |
|-----------|-------|
| HTML5 | Structure |
| CSS3 | Styling |
| JavaScript | Functionality |
| localStorage | Data storage |

---

## ✨ Features

### For Users 👤
- 📝 **User Registration** — Signup with email and password
- 🔐 **Secure Login** — Email and password authentication
- 🔑 **Forgot Password** — Reset password via email
- 🚗 **Browse Vehicles** — View available vehicles
- 🛒 **Cart System** — Add vehicles to cart
- ✅ **Booking Success** — Confirmation after booking
- 📋 **Rental History** — View past bookings
- 🚪 **Logout** — Secure session management

---

## 📁 Project Structure
online-vehicle-rental-system/

css/

style.css              # Main stylesheet

js/

auth.js                # Authentication logic

images/                  # Vehicle and UI images

data/                    # Vehicle data

index.html               # Landing page

login.html               # Login page

signup.html              # Registration page

dashboard.html           # User dashboard

cart.html                # Cart page

history.html             # Rental history page

success.html             # Booking success page

forgot_password.html     # Password recovery page

README.md
---

## 🚀 How to Run Locally

**Option 1 — Live Server (Recommended):**
1. Open project in VS Code
2. Install **Live Server** extension
3. Right click `index.html`
4. Click **"Open with Live Server"** ✅

**Option 2 — Direct Browser:**
1. Clone the repository:
```bash
git clone https://github.com/abhiramreddymada/online-vehicle-rental-system.git
```
2. Open `index.html` in any browser ✅

---

## 🔐 Authentication

This project uses **localStorage** for authentication:
Signup → saves email + password to localStorage

Login  → validates credentials from localStorage

Logout → clears session from localStorage

Forgot Password → updates password in localStorage
---

## 📸 Screenshots

| Page | Description |
|------|-------------|
| Home | Landing page with vehicle listings |
| Login | User authentication |
| Dashboard | User dashboard after login |
| Cart | Selected vehicles |
| History | Past rental bookings |

---

## 🔮 Future Enhancements

🔜 Backend integration with Node.js/Firebase

🔜 Payment gateway integration

🔜 Real-time vehicle availability

🔜 Admin dashboard

🔜 Email notifications

🔜 Mobile responsive design
---

## 📄 License

This project is for educational purposes.

---

*Built with ❤️ using HTML, CSS and JavaScript 🚗*