# online-code-editor
# 🌐 Online Code Editor with User Authentication & Admin Panel

A full-featured **Online Code Editor** built with **PHP** offering secure user registration, login, password management, multi-language code compilation, personal notes management, theme switching, and an admin control panel.

---

## 📌 Features

### 🔐 User Authentication
- User Registration with **Gmail**.
- **OTP Verification** before account activation.
- Password conditions:
  - Minimum 8 characters.
  - At least 1 special character.
  - At least 1 uppercase letter.
  - At least 1 lowercase letter.
- Confirm password (enter twice).
- Forgot password feature:
  - OTP sent to Gmail.
  - OTP verification before password reset.

---

### 🏠 Home Interface (Post-Login)
- **Profile Page**
  - View & update profile photo, name, date of birth.
  - Change password.
  - Set user role.
- **CodeLab**
  - Choose from multiple language compilers:
    - C, C++, Java, Python, R, JavaScript, HTML/CSS/JS, C#.
  - Write and run code online.
- **Notes Section**
  - Create and save personal notes.
  - View all saved notes.
  - Search notes.
  - Edit and delete specific notes.
  - Download selected or all notes.

---

### 🎨 Theme Control
- Switch between **Dark Mode** and **Light Mode**.

### 🚪 Logout
- Secure session management and logout.

---

### 🛠️ Admin Panel
- Admin Login:
  - **Email:** `yash@gmail.com`
  - **Password:** `12345`
- Manage users:
  - View all user details.
  - Edit user data.
  - Delete users.
  - Download user details in **PDF format**.
- Logout option.

---

## 🖥️ Technologies Used

- **PHP**
- **HTML / CSS / JavaScript**
- **MySQL** (Database)
- **SMTP Mail API** (for sending OTP)
- **PDF Export Library** (for admin download)
- **Online Compiler APIs** (language-specific)

---
