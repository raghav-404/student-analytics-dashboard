<<<<<<< HEAD
# Student Analytics Dashboard (SIS Nexus)

A comprehensive, full-stack Student Information System (SIS) designed for modern educational institutions. This platform transforms raw student data (CSV) into actionable, real-time insights with a futuristic, highly interactive user interface.

## 🚀 Features

- **Multi-View Operations**: Seamless navigation between Dashboard, Students, Analytics, Reports, and Admin views.
- **Full CRUD Management**: View, filter, edit, and delete student records directly from the web interface.
- **Advanced Analytics**:
  - Time-series performance trends.
  - Subject vs. Semester heatmaps.
  - Risk distribution tracking (AI-driven insights).
- **Interactive Visualizations**: Powered by `react-chartjs-2` (Bar, Doughnut, and Line charts).
- **Report Generation**: Automatically generate and print beautiful student report cards.
- **Global Command Palette**: Press `Ctrl+K` from anywhere in the app to instantly search for a student.
- **Smart Data Uploads**: Drag-and-drop CSV parser with active "Data Health" monitoring identifying missing fields natively.

## 🛠️ Tech Stack

- **Frontend**: React.js, Vite, Chart.js, HTML5, Vanilla CSS (Futuristic/Glassmorphism theming)
- **Backend**: Node.js, Express, Multer (file uploads), csv-parser
- **Storage**: In-Memory state management (with clean extensibility for MongoDB/PostgreSQL)

## 📦 Installation & Setup

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### 1. Clone the repository
```bash
git clone https://github.com/Nikhita48Raj/student-analytics-dashboard.git
cd student-analytics-dashboard
```

### 2. Start the Backend Server
The Node.js backend processes file uploads and hosts the REST API on port `5000`.
```bash
cd backend
npm install
node server.js
```

### 3. Start the Frontend Application
The Vite server hosts the React application and proxies API requests. Open a new terminal window:
```bash
cd frontend
npm install
npm run dev
```

### 4. Access the Application
Open your browser and navigate to `http://localhost:5173`. 
*Note: You can use the `legacy/sample-data.csv` file to test the Admin upload workflow if you don't have your own dataset.*

## 📁 Repository Structure

- `/frontend`: The modern React application built using Vite.
- `/backend`: The Express server acting as the bridge for data mutations and CSV parsing.
- `/legacy`: Contains the original static vanilla JS iteration of the dashboard.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License
This project is open-source and available under the [MIT License](LICENSE).
=======
📊 Student Analytics Dashboard (SIS Nexus)

A full-stack Student Information System (SIS) designed for modern educational institutions.
This platform transforms raw student data (CSV) into actionable, real-time insights with a futuristic and highly interactive UI.

🚀 Features
🧭 Multi-View Navigation

Easily switch between different modules:

Dashboard
Students
Analytics
Reports
Admin Panel
✏️ Full CRUD Functionality

Manage student records directly from the interface:

View student profiles
Filter records
Edit details
Delete entries
📈 Advanced Analytics

Powerful insights to support decision making:

⏳ Time-series performance tracking
🔥 Subject vs Semester heatmaps
⚠️ AI-based risk distribution insights
📊 Interactive Visualizations

Dynamic charts built with react-chartjs-2:

Bar charts
Doughnut charts
Line graphs
🧾 Report Generation

Generate professional student report cards instantly.

⚡ Global Command Palette

Press Ctrl + K to instantly search for students from anywhere in the app.

📂 Smart CSV Uploads

Drag-and-drop CSV upload with built-in data validation:

Detect missing fields
Monitor data health
Instant parsing
🛠️ Tech Stack
Frontend
⚛️ React.js
⚡ Vite
📊 Chart.js
🎨 HTML5
💎 Vanilla CSS (Glassmorphism + Futuristic UI)
Backend
🟢 Node.js
🚏 Express.js
📤 Multer (file uploads)
📑 csv-parser
Storage
🧠 In-memory state management
🔌 Easily extendable to MongoDB / PostgreSQL
📦 Installation & Setup

![Upload](screenshots/admin.png)
![Dashboard](screenshots/dashboard.png)
![Students](screenshots/students.png)
![Analytics](screenshots/analytics.png)
![Reports](screenshots/report.png)

Make sure Node.js is installed on your system.

🔗 Download Node.js: https://nodejs.org/

1️⃣ Clone the Repository
git clone https://github.com/Nikhita48Raj/student-analytics-dashboard.git
cd student-analytics-dashboard
2️⃣ Start Backend Server

The backend processes CSV uploads and exposes REST APIs on port 5000.

cd backend
npm install
node server.js
3️⃣ Start Frontend Application

Run the React app using Vite (open a new terminal):

cd frontend
npm install
npm run dev
4️⃣ Open the App

Visit:

http://localhost:5173

You can test the upload feature using:

legacy/sample-data.csv
📁 Project Structure
student-analytics-dashboard/
│
├── frontend/        # React + Vite frontend
├── backend/         # Express API server
├── legacy/          # Original vanilla JS version
└── README.md
💡 Use Cases

✔ Academic performance monitoring
✔ Student risk detection
✔ Institutional analytics dashboards
✔ Education data visualization projects

>>>>>>> ad768c6476c413b48aca264f0dd40caf4ba7f13b
