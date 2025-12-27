# 🧑‍💼 HR Management System

A web-based **Human Resources (HR) Management System** designed to help organizations manage employees, attendance, salaries, and core HR operations efficiently from a single platform.

---

## 🚀 Features

### 👤 Employee Management
- Add, edit, and deactivate employees
- Store personal, job, and contract details
- Assign departments, positions, and roles

### ⏱ Attendance Management
- Daily attendance tracking (check-in / check-out)
- Manual and automatic attendance records
- Absence, late arrival, and overtime tracking
- Monthly attendance reports

### 💰 Salary & Payroll
- Salary structure management
- Automatic salary calculation based on:
  - Attendance
  - Overtime
  - Deductions
  - Bonuses
- Monthly payroll generation
- Salary history per employee

### 🏖 Leave Management
- Leave requests and approvals
- Annual, sick, and unpaid leave tracking
- Leave balance calculation

### 📊 Reports & Analytics
- Attendance reports
- Salary and payroll reports
- Employee performance and summary reports
- Export reports (PDF / Excel)

### 🔐 User Roles & Permissions
- Admin
- HR Manager
- Accountant
- Employee
- Role-based access control

---

## 🛠 Tech Stack

- **Backend:** Laravel
- **Frontend:** Blade / Vue / React (depending on implementation)
- **Database:** MySQL / PostgreSQL
- **Authentication:** Laravel Auth
- **Authorization:** Policies & Roles
- **API:** RESTful APIs (optional)

---



## Installation

Follow these steps below to install the application.

Or Watch the installation process on [Youtube](https://youtu.be/UHkrsyBcMRM)

- Clone the repository using your termina or command prompt
```php

git clone https://github.com/muhammadmajd/HRS.git hr
```
```
cd smarthr

```

- Install dependencies
    - Composer

	```
	composer install

	```


- Create your database

- Rename .env.example to .env Or copy and paste at project root directory and rename the file .env .You can also use this command.

```
cp .env.example .env

```

- Generate app key with this command
```
php artisan key:generate

```
- Install Reverb
```
php artisan reverb:install

```

- Set database connection to your database in the .env file. Make sure to set APP_URL to make your domain.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=smarthr
DB_USERNAME=root
DB_PASSWORD=

```

- Run migrations and seeders

```
php artisan migrate:fresh --seed; php artisan module:migrate --all --seed

```

- Create Symlink
```
php artisan storage:link
```




