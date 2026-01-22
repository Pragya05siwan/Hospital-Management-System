# Hospital Management System

A comprehensive web-based application developed using the **Django** framework to manage hospital operations efficiently. The system provides distinct dashboards for Admins, Doctors, and Patients to ensure seamless coordination.

---

## Developed By
- **Pragya**

---

## Key Features

### 🔐 Admin Module
- **User Management:** Full authority to register, approve, reject, or delete Doctor and Patient accounts.
- **Invoicing:** Generate and download automated PDF invoices including medicine costs, room charges, and consultancy fees.
- **Appointment Handling:** Review and approve appointment requests made by patients.

### 🩺 Doctor Module
- **Professional Registration:** Apply for hospital registration (subject to Admin approval).
- **Patient Monitoring:** View details of assigned patients, symptoms, and medical history.
- **Schedule Management:** Access personal appointment lists and manage discharged patient records.

### 🏥 Patient Module
- **Account Creation:** Register and login to the portal (subject to Admin approval).
- **Appointment Booking:** Request appointments with specific doctors and track approval status.
- **Digital Invoices:** Access and download PDF invoices once the discharge process is completed by the Admin.

---

## Technical Setup & Installation

1. **Prerequisites:**
   Ensure Python (3.7 or higher) is installed on your system. Run the following commands to install dependencies:
   ```bash
   pip install django==3.0.5
   pip install django-widget-tweaks
   pip install xhtml2pdf

 * Database Configuration:
   Navigate to the project directory and execute migrations:
   python manage.py makemigrations
python manage.py migrate

 * Running the Application:
   Start the local development server:
   python manage.py runserver

   Access the system at: http://127.0.0.1:8000/
Important Notes
 * Email Service: To enable the 'Contact Us' mail feature, update the EMAIL_HOST_USER and EMAIL_HOST_PASSWORD in the settings.py file.
 * Operational Flow: At least one doctor must be registered and approved in the system before a patient can be admitted.
Disclaimer
This project is developed for academic purposes and demonstration of web development skills using Django.
