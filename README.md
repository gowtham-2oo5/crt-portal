# CRT Portal - Demo Guide

> A full-stack web application for managing Career Readiness Training at KL University

## 🔗 Live Demo

- **Frontend**: https://crt-portal-iota.vercel.app
- **Backend API**: https://crt-portal-api.gows.me
- **API Documentation**: https://crt-portal-api.gows.me (Swagger UI)

## 📦 Source Code

- **Frontend Repository**: https://github.com/gowtham-2oo5/CRT_Portal-client
- **Backend Repository**: https://github.com/gowtham-2oo5/CRT_Portal-server

## 🔐 Test Credentials

### Admin Account
- **Email**: `admin@kluniversity.in`
- **Password**: `Admin@CRT123`
- **OTP**: `123456` (default for testing)

### Faculty Account
- **Email**: `test@kluniversity.in`
- **Password**: `Faculty@CRT456`
- **OTP**: `123456` (default for testing)

---

## ✨ Key Features

### 🔒 Authentication & Security
- **Two-factor authentication** with email OTP
- Role-based access control (Admin/Faculty)
- Secure JWT token authentication
- Password reset functionality

### 👨‍💼 Admin Features

#### User Management
- Create, edit, and manage faculty accounts
- Bulk user import via CSV
- View all registered users
- Assign roles and permissions

#### Student Management
- Add and manage student records
- Bulk student import
- Section assignment
- Student data export

#### Schedule Management
- Create and manage training schedules
- Assign faculty to time slots
- Room allocation
- Smart scheduling with conflict detection
- Weekly calendar view

#### Attendance Tracking
- View attendance reports across all sections
- Filter by date, faculty, or section
- Export attendance data
- Real-time attendance statistics

#### Reports & Analytics
- Attendance summary reports
- Faculty performance metrics
- Section-wise analytics
- Data export in multiple formats (CSV, Excel)

#### System Settings
- Configure time slots
- Manage rooms and venues
- Bulk operations for data management
- System-wide configurations

### 👨‍🏫 Faculty Features

#### My Dashboard
- Quick overview of today's schedule
- Upcoming sessions
- Recent attendance records
- Personal statistics

#### Attendance Management
- Mark attendance for assigned sessions
- View current time slot
- Batch attendance marking
- Late submission with reason
- Attendance history

#### My Timetable
- View personal weekly schedule
- Session details (room, section, time)
- Calendar view
- Upcoming sessions

#### Reports
- View attendance reports for my sessions
- Student-wise attendance tracking
- Export my session data

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 14 (React)
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **State Management**: React Hooks
- **Deployment**: Vercel

### Backend
- **Framework**: Spring Boot 3.5
- **Language**: Java 21
- **Database**: MySQL (AWS RDS)
- **Authentication**: JWT + Spring Security
- **Caching**: Redis
- **API Documentation**: Swagger/OpenAPI
- **Deployment**: AWS EC2 with Nginx

---

## 🎯 What Makes This Special

1. **Real-time Updates**: Live attendance tracking and schedule updates
2. **Smart Scheduling**: Automatic conflict detection when creating schedules
3. **Bulk Operations**: Import hundreds of users/students via CSV
4. **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
5. **Secure**: Two-factor authentication and role-based access
6. **Production Ready**: Deployed on cloud infrastructure with HTTPS

---

## 📱 How to Test

1. **Login**: Use the test credentials above
2. **Admin Flow**: 
   - Navigate to Users → Create a new faculty
   - Go to Schedule Management → Create a training schedule
   - Check Reports → View attendance analytics
3. **Faculty Flow**:
   - View your timetable
   - Mark attendance for a session
   - Check your reports

---

Built by an aspiring software developer with freelance experience.
