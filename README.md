# Classroom Manager

## Group Members

| Name              | ID.NO         | Section |  
|-------------------|--------------|----------|  
| Milki Legesse     | UGR/9040/15   | 2       |  
| Tesfanesh Asefa   | UGR/1233/15   | 3       |  
| Yitbarek Alemu    | UGR/7554/15   | 1       |  

## Project Overview

**Project Name:** Classroom Manager

**Objective:**  
Classroom Manager is a mobile app designed to help students and student representatives manage classroom bookings and schedules. The app allows users to check room availability, book classrooms, view class schedules, and track room occupancy. It simplifies the process of managing classroom usage, ensuring that rooms are booked and used efficiently.

**Scope:**  
This app is intended for **student representatives** who can book classrooms and manage schedules, and for **students** who can view classroom availability and their class schedules.

---

## Features

### For Student Representatives (Full Control)
1. **Classroom Booking & Occupancy Management**  
   - **Create Bookings**: Student representatives can reserve classrooms for lectures or meetings directly from the app.
   - **Check Room Availability**: They can view if a classroom is free or occupied at any given time.
   - **Modify Bookings**: If needed, they can change the booking or reschedule the classroom reservation.
   - **Cancel Bookings**: If a class or meeting is canceled, they can remove the reservation to make the room available for others.

2. **Class Schedule Management**  
   - **Add Class Schedules**: Representatives can add, modify, or remove class schedules directly from the app.
   - **View Class Schedules**: They can easily check and verify all class schedules for the semester, including the time and classroom assignments.

3. **Auto-Release Unused Classrooms**  
   - **Room Auto-Release**: If a classroom that was booked is not used within 15 minutes, it will automatically become available again. This feature helps avoid unused rooms being blocked for long periods.

### For Students (Limited Access)
1. **Classroom Occupancy Viewing**  
   - **Check Room Availability**: Students can check if a classroom is free or occupied before heading to their next class.
   
2. **View Class Schedule**  
   - **Access Personal Schedule**: Students can view their class schedules to know when and where their next class is, without needing to rely on printed timetables.

---

## Technologies Used

### Frontend
- **Flutter**: The mobile app is developed using Flutter, which allows us to create a smooth and responsive interface that works across both Android and iOS devices.
- **Dart**: Flutter uses Dart, a programming language, for building the app’s functionality.

### Backend
- **Node.js**: This is used to handle requests made by the app, such as booking classrooms or viewing schedules.
- **Express.js**: This framework helps manage the app’s backend logic, including the booking system and schedule management.

### Database
- **MongoDB**: A database used to store important data like classroom bookings, schedules, and room occupancy statuses.

---

## Installation and Setup

### Prerequisites
- **Flutter SDK** (Ensure that you have Flutter set up on your machine)
- **Node.js** (v16 or higher)
- **MongoDB** instance (local or cloud-based)
- **Git**

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Classroom_Manager.git
   cd classroom-manager
