# EventSphere 🎉

EventSphere is a **Collaborative Event Management Platform** designed to streamline how events are organized and experienced within a college campus. From showcasing events to managing volunteers and gathering feedback, EventSphere serves as a one-stop platform for both users and admins.

---

## 🔧 Tech Stack

- **Frontend:** HTML, CSS, JavaScript, JSP (JavaServer Pages)
- **Backend:** Java Servlets
- **Database:** MySQL
- **IDE:** Eclipse
- **Server:** Apache Tomcat

---

## ✨ Features

### For Users:
- User registration and login
- Personalized dashboard showing ongoing/upcoming college-specific events
- Feedback submission for attended events

### For Admins:
- Admin login and secure access to the dashboard
- Create, update, and manage events
- Assign tasks to volunteers
- View user list, coordinator list, and feedback submitted by users

---

## 🚀 How to Run the Project

1. **Clone the Repository** or download the source files.
2. **Import the project into Eclipse** as a Dynamic Web Project.
3. **Set up MySQL Database:**
   - Create a database (e.g., `eventsphere`)
   - Import the provided SQL file (if available) or create required tables:
     - `users`, `events`, `feedback`, etc.
4. **Update Database Configuration:**
   - Go to `com.eventsphere.db.DBConnection.java`
   - Set your MySQL URL, username, and password

5. **Run the Project:**
   - Deploy the project on Apache Tomcat Server
   - Access it via `http://localhost:8080/EventSphere`
  
---

## 👨‍💻 Author

**Nikhil Kumar**  
B.Tech in Computer Science and Technology  
St. Andrews Institute of Technology and Management (SAITM), Gurgaon  

---

## 📌 Notes

- Currently built for a **single college system**
- Future scope includes:
  - Multi-college event support
  - Ticket booking system
  - Notification and reminder module

---

## 📃 License

This project is for academic use as part of the pre-final year minor project submission at SAITM.
