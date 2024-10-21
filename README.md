# PW Docker Web App

This project is a simple application using Flask (frontend), FastAPI (backend), and PostgreSQL (database), containerized with Docker.

## Setup

1. **Clone the repo**:
   ```bash
   git clone https://github.com/Chouaib-Djerdi/TP-Docker.git
   cd TP-Docker
   ```

2. **Create a `.env` file** with:
   ```bash
   POSTGRES_USER=your_postgres_user
   POSTGRES_PASSWORD=your_postgres_password
   POSTGRES_DB=student_db
   ```

3. **Run the app**:
   ```bash
   docker-compose up --build
   ```

4. **Access the app**:
   - Add a student: [http://localhost:8090/add](http://localhost:8090/add)
   - View all students: [http://localhost:8090/all](http://localhost:8090/all)
   - Adminer DB access: [http://localhost:8091](http://localhost:8091)
   - API Docs: [http://localhost:8080/docs](http://localhost:8080/docs)

5. **Stop the app**:
   ```bash
   docker-compose down
   ```
