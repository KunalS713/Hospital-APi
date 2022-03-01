Hospital API
A NodeJS and MongoDB built API for hospital doctors to keep track of their patients with Covid19 test reports.

Technologies Used
Nodejs
Express
MongoDB for database
Prerequisites
MongoDB
Node.js 10+
Command Line Tools
Visual Studio Code
Installation
# Get the latest snapshot
git clone https://github.com/KunalS713/Hospital-API.git 

# Change directory
cd myproject

# Install NPM dependencies
npm install

# Then simply start your app
npm start

# The Server should running at: http://localhost:8000/
Folder Structure
app
├── config
│ --- ├── mongoose.js
│ --- └── passport-jwt-strategy.js
├── controllers
│ --- ├── doctors_controller.js
│ --- ├── patients_controller.js
│ --- └── reports_controller.js
├── models
│ --- ├── doctor.js
│ --- ├── patient.js
│ --- └── report.js
├── routes
│ --- ├── api
│ ----│ -- ├── v1
│ --- │ -- │ -- ├── doctors.js
│ --- │ -- │ -- ├── index.js
│ --- │ -- │ -- ├── patients.js
│ --- │ -- │ -- └── reports.js
│ ----│ -- └── index.js
│ --- └── index.js
├── server.js
├── package.json
├── package-lock.json
└── readme.md