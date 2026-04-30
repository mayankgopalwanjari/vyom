A Machine Learning-Based System for Optimizing Aircraft Arrivals in Air Traffic Control


🚀 Installation Guide – VYOM
📌 Prerequisites

Make sure you have installed:

Java JDK 17 (or higher)
Maven
PostgreSQL
Git
IntelliJ IDEA / Eclipse
📌 Step 1: Clone the Repository
git clone https://github.com/mayankgopalwanajri/vyom.git
cd vyom
📌 Step 2: Configure Java
Set JAVA_HOME to your JDK path
Verify installation:
java -version
javac -version
📌 Step 3: Setup Database (PostgreSQL)
Open PostgreSQL
Create a database:
CREATE DATABASE vyom_db;
Update database credentials in application.properties:
spring.datasource.url=jdbc:postgresql://localhost:5432/vyom_db
spring.datasource.username=your_username
spring.datasource.password=your_password
📌 Step 4: Build the Project
mvn clean install
📌 Step 5: Run the Application
mvn spring-boot:run

Or using wrapper:

./mvnw spring-boot:run

(Windows)

mvnw.cmd spring-boot:run
📌 Step 6: Access the Application

Open your browser:

http://localhost:8080
📌 Step 7: Load Sample Data
Add sample aircraft data in CSV
Import into database or through API
📌 Step 8: Test APIs (Optional)

Use Postman:

/arrival-data
/predict
/optimize-sequence
/taxi-route
⚠️ Troubleshooting
If Java not detected:
Check JAVA_HOME
Add %JAVA_HOME%\bin to PATH
If DB connection fails:
Check PostgreSQL service is running
Verify username/password
✅ Ready to Use

Your VYOM system should now be running successfully 🎯
