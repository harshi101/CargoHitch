# 🚚 CargoHitch - Smart Partial-Load Logistics & Cargo Sharing Platform

CargoHitch is a smart logistics platform designed to reduce empty truck runs by enabling real-time sharing of unused cargo space. The system connects truck owners with small businesses and SMEs that need to transport partial loads, making logistics more affordable, efficient, and environmentally sustainable.

By focusing on partial-load optimization instead of full-load transport, CargoHitch improves truck utilization, reduces fuel wastage, and lowers carbon emissions while supporting small-scale businesses.

## 🌍 Problem Statement

In the logistics industry:

- Nearly 20–30% of trucks run empty or underutilized
- Small businesses struggle to find affordable transport for small shipments
- Existing logistics platforms focus mainly on full truckloads
- This results in higher fuel costs, inefficiency, and environmental impact

CargoHitch bridges this gap by providing a technology-driven solution for real-time cargo space sharing.

## 🎯 SDG Alignment

CargoHitch supports multiple UN Sustainable Development Goals (SDGs):

- SDG 9 – Industry, Innovation & Infrastructure
- SDG 11 – Sustainable Cities & Communities
- SDG 12 – Responsible Consumption & Production
- SDG 13 – Climate Action

## 📌 Features

### 👤 User Module (Businesses / SMEs)
- Secure registration and login
- Enter pickup & drop locations
- Submit cargo requests (partial loads)
- View matched trucks
- Booking history
- Cost-effective transport access

### 🚛 Truck Owner Module
- Secure registration and login
- Route and capacity management
- View available cargo requests
- Accept partial-load bookings
- Improved truck utilization
- Increased driver income

### ⚙️ Core Logistics Features
- Real-time cargo-to-truck matching
- Partial-load sharing system
- Route-based matching
- Reduced empty miles
- Scalable logistics model

### 👨‍💼 Admin Module (Planned)
- User management
- Booking monitoring
- Platform analytics
- System performance tracking

## 🛠️ Technologies Used
### Frontend
- React.js
- HTML5
- CSS3
- JavaScript (ES6+)

### Backend
- Spring Boot
- Java
- REST APIs

### Database
- MySQL

### Tools & Platforms
- Visual Studio Code
- MySQL Workbench
- Postman
- Git & GitHub

## 📂 Project Structure
```      
CargoHitch/
│── frontend/
│   ├── src/
│   ├── components/
│   ├── assets/
│   ├── App.jsx
│   ├── main.jsx
│── backend/
│   ├── controllers/
│   ├── services/
│   ├── repositories/
│   ├── models/
│   ├── config/
│── database/
│── docs/
│── README.md
```

## 🚀 Features Implemented
- React frontend setup using Vite
- Spring Boot backend structure
- MySQL database schema design
- User registration & authentication
- Cargo request handling
- Route-based matching logic
- API testing using Postman

## ⚙️ Installation & Setup

### 1️. Clone the Repository
```
git clone https://github.com/yourusername/CargoHitch.git
cd CargoHitch
```
### 2.Frontend Setup
```
cd frontend
npm install
npm run dev
```

Frontend runs at:
```
http://localhost:5173
```

### 3.Backend Setup
```
cd backend
mvn clean install
java -jar target/backend-0.0.1-SNAPSHOT.jar
```

Backend runs at:
```
http://localhost:8080
```
### 4️.Database Configuration
Create a MySQL database:
```
CREATE DATABASE cargohitch;
```
Update application.properties:
```
spring.datasource.url=jdbc:mysql://localhost:3306/cargohitch
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
````

## 🧪 Experimental Setup & Data Handling
- Sample logistics datasets (routes, load capacity, shipment requests)
- Simulated real-time matching scenarios
- User-input based cargo and route data
- Tested on local development environment

## 📊 Results & Impact
- Reduced empty truck mileage
- Lower transportation cost for SMEs
- Improved logistics efficiency
- Reduced fuel consumption and emissions
- Scalable and sustainable logistics model

## 🚀 Future Enhancements
- AI-based route optimization
- Dynamic pricing model
- Real-time GPS tracking
- Mobile application (Android & iOS)
- Advanced analytics dashboard
- Large-scale pilot deployment
- Integration with IoT & logistics partners

## 🎯 Applications
- Smart logistics platforms
- SME transportation support
- Green logistics solutions
- Smart city supply chains
- Sustainable transport systems

## 👨‍💻 Team Members

**Team Name:**  Pixel Pirate

- Harshitha T – CSE
- Harshini S – CSE
- Hitesha G – CSE
- Ishwarya S – CSE

### Mentor:
Ms. Angalaparameshwari  
Assistant Professor,CSE  
Rajalakshmi Institute of Technology

## 📄 License
This project is developed for academic, research, and educational purposes.

## ⭐ Acknowledgements
- Faculty mentors for guidance and support
- Open-source community
- React, Spring Boot, and MySQL documentation

## ⚙️ Available Scripts

In the project directory, you can run:

### `npm start`
Runs the application in development mode.  
Open http://localhost:3000 to view it in the browser.

The page will reload automatically when you make changes.

### `npm run build`
Builds the application for production and optimizes it for best performance.

The build folder is ready for deployment.
