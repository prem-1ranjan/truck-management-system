# Truck Management System

A Java JDBC based backend application to manage truck records using MySQL database.

## Tech Stack
☕ Java  
🔗 JDBC  
🗄️ MySQL 
⚙️ Maven

## Features
- Add Truck 🚛
- Get Truck By ID 🔍
- Update Truck 🛠️
- Delete Truck ❌
- Get All Trucks 📋

### Database Table

```sql
CREATE TABLE truck(
 id INT PRIMARY KEY AUTO_INCREMENT,
 name VARCHAR(50),
 model VARCHAR(50),
 capacity INT,
 driver_name VARCHAR(50)
);
```
## Project Structure

model → Entity classes  
service → Business logic  
util → Database connection  
App.java → Application entry point
