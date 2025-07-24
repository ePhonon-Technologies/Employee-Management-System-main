

<div align="center">
  <h1>Modern Employee Management Solution</h1>
  <p>Streamlining HR operations with cutting-edge MERN stack technology</p>
  
  <p align="center">
    <img src="https://img.shields.io/badge/status-under%20development-yellow" alt="Project Status">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="License">
    <img src="https://img.shields.io/badge/stack-MERN-9cf" alt="Tech Stack">
  </p>
</div>

> [!IMPORTANT]
> **Note:** This project is currently under active development. Features and documentation are being regularly updated.

## 📸 Application Preview

<div align="center">
  <h3>✨ Key Screenshots</h3>
  
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 20px 0;">
    <img src="https://github.com/user-attachments/assets/75dc7a8d-d816-4597-b89c-6ade8998afd9" alt="EMS Entry Page" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <img src="https://github.com/user-attachments/assets/ca4c14e0-dcfd-41b2-83cd-1ad67a474142" alt="HR Dashboard" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <img src="https://github.com/user-attachments/assets/b84d5027-1cc2-4083-aa89-770db32a2b39" alt="Employees Data" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  </div>
</div>

## 🌟 Core Features

| Category | Features |
|----------|----------|
| **🔐 Authentication** | JWT-based secure login, Role-based access control |
| **👥 Employee Portal** | Personal dashboard, Attendance tracking, Leave management |
| **📊 HR Management** | Employee records, Department management, Recruitment tracking |
| **💼 Operations** | Salary processing, Corporate calendar, Dynamic notifications |
| **✉️ Communication** | Email transactions, Real-time alerts, Notice distribution |

## 🛠 Technology Stack

**Frontend:**
- React.js with Vite
- Redux for state management
- Tailwind CSS + ShadCN UI components
- Chart.js for data visualization

**Backend:**
- Node.js with Express.js
- MongoDB with Mongoose ODM
- JWT for authentication
- Nodemailer for email services

## ⚙️ Installation Guide

```bash
# Clone the repository
git clone https://github.com/Darsh-Jogi/Employee-Management-System.git
cd Employee-Management-System

# Install backend dependencies
cd server && npm install

# Install frontend dependencies
cd ../client && npm install

# Configure environment variables
cp .env.example .env
```

### Environment Variables

**Server (.env)**
```ini
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
MAILTRAP_TOKEN=your_mailtrap_token
PORT=5000
```

**Client (.env)**
```ini
VITE_EMPLOYEE_API=http://localhost:5000/api
```

## 🏃‍♂️ Running the Application

1. Start backend server:
```bash
cd server
npm run server
```

2. Start frontend development server:
```bash
cd ../client
npm run dev
```

## 🗺 Project Roadmap

```mermaid
gantt
    title EMS Development Phases
    dateFormat  YYYY-MM-DD
    section Core Features
    Employee Dashboard       :done,    des1, 2023-10-01, 2023-11-15
    HR Management System    :active,  des2, 2023-11-16, 2024-01-31
    section Advanced Features
    Recruitment Module      :         des3, 2024-02-01, 2024-03-15
    Analytics Dashboard     :         des4, 2024-03-16, 2024-04-30
```

## 🤝 Contributing

We welcome contributions! Please:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request




