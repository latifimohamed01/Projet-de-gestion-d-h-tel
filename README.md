# 🏨 Hotel Property Management System (PMS)

A comprehensive Hotel Property Management System designed to simplify hotel operations and improve the experience of both customers and hotel staff. The platform consists of a Flutter mobile application for clients, a React-based web dashboard for hotel staff, and a Node.js/Express backend API.

## 📁 Project Structure

```text
PMS/
│
├── pms-mobile/                 # Flutter Mobile Application (Client)
│   ├── lib/
│   │   ├── core/
│   │   ├── data/
│   │   └── presentation/
│   └── pubspec.yaml
│
├── pms-web/                    # React Web Dashboard (Hotel Staff)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── manager/
│   │   │   └── receptionist/
│   │   └── services/
│   └── package.json
│
├── pms-backend/                # Node.js + Express REST API
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│   ├── .env
│   └── package.json
│
└── database/
    └── schema.sql
```

## 📱 Mobile Application – Client

The mobile application provides customers with an intuitive interface to explore rooms, manage their profiles, and make reservations.

| Screen | Description |
|---|---|
| Login | User authentication using email and password. |
| Registration | Account creation with personal information, including name, email, phone number, and password. |
| Discover | Browse room categories and explore top-rated rooms. |
| Room Details | View room photos, descriptions, prices, capacity, and reservation options. |
| My Reservations | View and manage personal reservations. |
| Profile | Display personal information and account actions. |
| Edit Profile | Update name, email, phone number, and profile picture. |

## 🖥️ Web Application – Hotel Staff

The web dashboard provides role-based access to hotel staff, allowing administrators, managers, and receptionists to manage daily hotel operations.

### 🔐 Authentication (All Staff)

| Screen | Description |
|---|---|
| Staff Login | Authentication using email and password. |
| Code Verification | Verify identity using a six-digit code sent by email. |
| New Password | Reset the account password. |

### 👨‍💻 Administrator Dashboard

| Screen | Description |
|---|---|
| Dashboard | Overview of rooms, reservations, occupancy rates, and revenue. |
| User Management | View, edit, and delete user accounts. |
| Room Management | Complete room management with CRUD operations. |
| Reported Issues | View and manage problems reported within the hotel. |

### 👔 Manager Dashboard

| Screen | Description |
|---|---|
| Employees | Manage employee information and salaries. |
| Schedule | Organize employee schedules using a calendar. |
| Budget | Monitor and review hotel financial information. |

### 🛎️ Receptionist Dashboard

| Screen | Description |
|---|---|
| Add Reservation | Create reservations with automatic price calculation. |
| Reservations List | View, update, and cancel reservations. |
| Employee Schedule | Consult staff working schedules. |

## 🔮 Future Improvements

The following features are planned as potential future enhancements:

- Integration with external services, including calendars and messaging platforms.
- Advanced analytics and reporting tools.
- Customer reviews and feedback management.
- Online payment gateway integration.
- Multilingual support (Arabic, French, and English).

## 🛠️ Technologies Used

- **Mobile:** Flutter & Dart
- **Frontend:** React.js
- **Backend:** Node.js & Express.js
- **Database:** SQL-based database (see `database/schema.sql`).
