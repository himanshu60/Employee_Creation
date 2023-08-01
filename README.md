
# Employee Creation/Updation and Deletion App

A web application built with Node.js, Express, MongoDB, and vanilla JavaScript for managing employees. The app allows you to create, update, and delete employees. Each employee has a name, title, department, and annual salary.

## Deploy link: https://rad-strudel-4caeac.netlify.app/

# ScreenShot
![emp_creation](https://github.com/himanshu60/Employee_Creation/assets/65457075/786a0653-8fcc-4786-8c3e-f43c49f6c4ee)



## Features

- Create a new employee with name, title, department, and annual salary.
- Update an employee's department, title, and annual salary.
- Mark an employee as deleted (soft delete).
- View the list of all active employees.
- History and auditing logs for each employee action.


## Tech Stack

- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Frontend:** HTML, CSS, JavaScript

## Setup

1. Clone the repository.
 ```
   git clone https://github.com/your-username/employee-app.git
   cd employee-app
```
2. Initial setup
```
  npm init -y
  npm install express body-parser mongoose cors dotenv
```
3. Run the application
```
  nodemon app.js
```
  
 


