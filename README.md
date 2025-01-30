# Hospital Management System

## Overview
The **Hospital Management System** is a web application built using Django, designed to streamline hospital operations, including patient management, doctor assignments, and appointment scheduling.

## Features
- **User Authentication**: Secure login/logout for doctors, patients, and admin.
- **Patient Management**: Register, view, update, and delete patient records.
- **Doctor Management**: Assign doctors to patients and view schedules.
- **Appointment System**: Schedule, update, and manage patient appointments.
- **Dashboard**: Overview of hospital operations and patient statistics.
- **Billing System**: Manage invoices and patient payments.

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript (Bootstrap)
- **Database**: SQLite / PostgreSQL / MySQL (Configurable)
- **Deployment**: Gunicorn, Nginx (for production), Docker (optional)

## Installation
### Prerequisites
- Python 3.x
- Django framework
- Virtual Environment (optional but recommended)

### Steps
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Prajeesh-A/Hospital_Management.git
   cd Hospital_Management
   ```
2. **Create Virtual Environment** (Optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. **Install Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
4. **Apply Migrations**:
   ```sh
   python manage.py migrate
   ```
5. **Create Superuser**:
   ```sh
   python manage.py createsuperuser
   ```
6. **Run the Server**:
   ```sh
   python manage.py runserver
   ```
7. Open the browser and go to `http://127.0.0.1:8000/` to access the application.

## Usage
- **Admin Panel**: `http://127.0.0.1:8000/admin/`
- **User Login**: Doctors and patients can log in to access their respective dashboards.
- **Appointments**: Patients can schedule appointments with doctors.

## Deployment
- For production deployment, use **Gunicorn & Nginx**.
- **Docker Support**: A `Dockerfile` is included for containerized deployment.

## Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
For queries, contact [prajeep6@gmail.com] or open an issue in the repository.

---
Happy Coding! 🚀

