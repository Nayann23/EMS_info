# 🏢 Employee Management System (React)  

<br>  

❌ **Sorry, this project is private!** If you're really interested in this project, you can connect with me to discuss further.  <br>  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nayan-darokar-468a85294/) <br>

<br>  
 

## 📌 Features  

<br>  

| Feature | Description |
|---------|------------|
| ✅ **Admin Dashboard** | Manage employees, assign tasks, and track progress |
| ✅ **User Dashboard** | Employees can view, accept, decline, and complete tasks |
| ✅ **Task Assignment** | Admin can assign tasks to specific employees |
| ✅ **Task Status Updates** | Users can update task status (Pending, Accepted, Declined, Completed) |
| ✅ **Live Status Tracking** | Admin can see real-time task updates |
| ✅ **Authentication System** | Secure login for Admins & Users |
| ✅ **Responsive UI** | Works on desktop & mobile |
| ✅ **Notifications** | Users & Admins get alerts on task updates |

<br>  

## 🛠 Tech Stack  

<br>  

| Technology | Purpose |
|------------|---------|
| **React.js** | Frontend framework for building UI |
| **Node.js** | Backend server to handle API requests |
| **Express.js** | Backend framework for routing & authentication |
| **MongoDB** | NoSQL database to store users, tasks, and updates |
| **Socket.io** | Real-time communication for task status updates |
| **JWT (JSON Web Token)** | Secure authentication |
| **Material-UI / Tailwind CSS** | Modern UI design |

<br>  

## 📷 Screenshots  

<br>  

📊 **Admin Dashboard**  
👨‍💻 **User Dashboard**  
📝 **Task Assignment Page**  
📌 **Task Status Updates**  

<br>  

## 📌 User Roles & Permissions  

<br>  

| Role | Permissions |
|------|------------|
| **Admin** | Manage employees, assign tasks, view task progress |
| **User (Employee)** | View assigned tasks, update task status, accept/decline tasks |

<br>  

## 📌 Task Status Workflow  

1️⃣ **Admin assigns a task to an employee**  
2️⃣ **Employee sees the task in their dashboard**  
3️⃣ **Employee can Accept / Decline the task**  
4️⃣ **If Accepted, Employee can mark it as Completed once done**  
5️⃣ **Admin sees live status updates for all tasks**  

<br>  

## 📌 API Endpoints  

<br>  

| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | `/api/auth/register` | Register new users |
| POST | `/api/auth/login` | Login users |
| POST | `/api/tasks/create` | Admin assigns a new task |
| GET | `/api/tasks` | Get all tasks (Admin & User-specific) |
| PATCH | `/api/tasks/:id/status` | Update task status (Accept, Decline, Complete) |
| GET | `/api/users` | Get all users (Admin only) |

<br>  
