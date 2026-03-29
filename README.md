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
