# task_word
# README.md

## Project Overview
This project is a WordPress-based website developed for a fictional law firm, **Law Solutions LLP**, as part of a take-home assignment for a Junior WordPress Developer role. The website includes:

- A professional home page with hero and services sections, a testimonial slider, and a contact form.
- Newsletter subscription integrated with Mailchimp.
- Appointment booking functionality for consultations integrated with Simply Schedule Appointments.
- A responsive design for mobile and desktop devices.
- Database operations, including a custom table for storing client leads.

---I Used 6 Plugins 
1. Elementor + Pro Elements (For Design Pro features)
2. Contact Form 7 (For Contact Form)
3. Simply Schedule Appointments (For Schedule booking)
4. MC4WP: Mailchimp for WordPress (For Newsletter)
5. ElementsKit Lite (For extra addons)

## Setup Instructions for WordPress

1. **Install Local Server**:
   - Install a local server environment such as XAMPP, MAMP, or WAMP.
   - Start the Apache and MySQL modules.

2. **Download WordPress**:
   - Download WordPress from [https://wordpress.org](https://wordpress.org).
   - Extract the files to the `htdocs` folder (for XAMPP) or the equivalent for your local server.

3. **Create a Database**:
   - Open phpMyAdmin and create a new database (e.g., `task_word`).

4. **Set Up WordPress**:
   - Navigate to `http://localhost/task_word` in your browser.
   - Follow the installation prompts and connect WordPress to the database you created.

5. **Install Plugins**:
   - Install and activate the following plugins:
    1. Elementor  
    2. Contact Form 7 
    3. Simply Schedule Appointments 
    4. MC4WP: Mailchimp for WordPress 
    5. ElementsKit Lite 
    6. Pro Elements

6. **Import Theme and Demo Content**:
   - I used Hello Elementor theme

---

## Steps to Replicate the Project Locally

1. Clone the repository from GitHub:
   ```bash
   git clone <repository-url>
   ```

2. Copy the project files into your local server's `htdocs` (or equivalent) directory.

3. Import the Database:
   - Open phpMyAdmin.
   - Import the `task_word.sql` file provided in the repository into a new database.

4. Update the `wp-config.php` file:
   - Modify the following fields to match your local database setup:
     ```php
     define('DB_NAME', 'task_word');
     define('DB_USER', 'root');
     define('DB_PASSWORD', '');
     define('DB_HOST', 'localhost');
     ```

5. Access the Website:
   - Navigate to `http://localhost/task_word` in your browser.
   Wordpress dashboard credentials -- 
   -- username - admin
   -- password - admin@12

---
6. Live Server Details 
   I used Hostinger for update my website live 
   Link -  https://taskword.streamfeverr.com/
   If you want to access live website dashboard 
   -- username - abhishek1x22@gmail.com
   -- password - admin@12

7. Server Knowledge:
    I transferred my WordPress website from localhost to Hostinger by converting it into a zip file, uploading it to the `public_html` folder, and unzipping it. Then, I updated the `wp-config.php` file with the database credentials from the live server's phpMyAdmin.

    
## Contact
If you encounter any issues or have questions about the setup, please reach out to me at abhishekgoswami8080@gmail.com or 7620233279.
