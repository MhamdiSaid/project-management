# Project Management Application

## Tools Used
- **Backend:** Java 17, Spring Boot  
- **Frontend:** React with MUI  
- **Database:** PostgreSQL  

---

## Backend & Frontend Setup

### Prerequisites
- Java 17 installed  
- Maven installed  
- Node.js 18+ installed  
- npm installed  
- PostgreSQL running  

### Backend Configuration
The backend connects to PostgreSQL with the following credentials:

- **Database Name:** hahnSoftwareTest  
- **Username:** postgres  
- **Password:** postgres  

Uploaded files will be stored in `./upload` directory relative to backend root.

```bash
# Running Backend

cd backend
mvn clean install
mvn spring-boot:run


# Frontend Setup & Running
cd frontend
npm install
npm run dev


Frontend will run on http://localhost:3000 and communicate with the backend at http://localhost:8080.