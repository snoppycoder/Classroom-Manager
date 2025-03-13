
| No | Name            | ID         |
|----|:---------------:|:----------:|
| 1  | Milki Legesse   | UGR/9040/15|
| 2  | Tesfanesh Asefa | UGR/1233/15|
| 3  | Yitbarek Alemu  | UGR/7554/15|
# Classroom Manager

Classroom Manager is a scheduling and occupancy management system designed to streamline classroom usage in schools, universities, and training centers. It allows **student representatives** to efficiently book, track, and manage classroom availability while providing **students** with real-time access to schedules and room occupancy.

With an intuitive interface, users can **check room availability, reserve spaces, and avoid scheduling conflicts**. The system also includes **automated notifications and an auto-release feature** to optimize classroom usage.

---

## Features

### 1. Class Queue Management (Scheduling & Occupancy Tracking)

#### Roles & Permissions

##### 1. Student Representatives (Full Control)

- **Classroom Booking & Occupancy Management:**
  - ✅ **Create:** Can book classrooms for lectures or meetings.
  - ✅ **Read:** Can check room availability and occupancy.
  - ✅ **Update:** Can modify or reschedule bookings.
  - ✅ **Delete:** Can cancel a booking if needed.

- **Class Schedule Management:**
  - ✅ **Create:** Can add class schedules.
  - ✅ **Read:** Can check and verify class schedules.
  - ✅ **Update:** Can edit and reschedule classes.
  - ✅ **Delete:** Can remove or cancel a scheduled class.

##### 2. Students (Limited Access)

- **Classroom Occupancy & Schedule Viewing:**
  - ✅ **Read:** Can view classroom occupancy (to see if a room is available or occupied).
  - ✅ **Read:** Can check their class schedule.

---

### 2. Auto-Release Unused Classrooms

- If a **booked classroom is not used within 15 minutes**, it is **automatically released** for others to book.
- **Example:** If no one checks in within the set time, the system updates the room status to **available**.
- **Implementation Tip:** Uses a **simple timer + status check mechanism** to free up unused spaces.

---

## Installation & Setup

> (Add instructions here if required, such as environment setup, database configuration, etc.)

## Usage

> (Include details on how to use the system, navigation steps, or API documentation if applicable.)

---

## Contributing

Contributions are welcome! Please follow standard contribution guidelines and open an issue or pull request.

---

## License

> (Specify the license for your project, e.g., MIT License.)

a
