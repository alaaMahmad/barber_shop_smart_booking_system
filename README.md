# Barber Shop Smart Booking System

A comprehensive web application designed to eliminate long queues, chaotic timings, and overlapping bookings through an automated slot-management system, role-based access control (RBAC), and interactive UI cards.

## 🚀 Tech Stack
- **Backend**: Python, Django Framework, MySQL, Bcrypt
- **Frontend**: HTML5, CSS3 / Bootstrap, JavaScript, AJAX
- **Design**: Figma Wireframes

## 📌 Core Features
1. **Authentication & RBAC**: Secure user registration and login with `bcrypt` password hashing and strict `Regex` validation via Custom Managers.
2. **Interactive Services Catalog**: Dynamic service cards displaying names, durations, and prices.
3. **Smart Slot & Appointment Management**: Automated 30-minute tracking slots preventing overlapping bookings and managing booking windows.
4. **Barber & Admin Dashboard**: Complete management interface for barbers to track appointments, update pricing, and handle day-off exceptions (`BarberException`).
5. **AI Chatbot Assistant**: Integrated lightweight assistant widget to handle automated FAQ responses regarding prices, working hours, and booking info.
