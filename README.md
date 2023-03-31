
# CinicCare

ClinicCare is a web-based Hospital Management System designed to streamline hospital operations and provide better patient care. With an intuitive user interface, ClinicCare offers features like patient management, appointment scheduling, electronic medical records (EMR), billing and invoicing, inventory and pharmacy management, laboratory and radiology management, and staff management. The system also provides analytics and reporting tools to help hospital administrators make informed decisions. ClinicCare is designed with security and access controls in mind to ensure the confidentiality of patient data. With ClinicCare, healthcare providers can focus on providing quality care while improving hospital efficiency and patient satisfaction.





## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Features

- Patient management system
- Appointment scheduling and management
- Electronic medical records (EMR) system
- Billing and invoicing system
- Inventory management system
- Pharmacy management system
- Laboratory management system
- Radiology and imaging management system
- Bed and ward management system
- Surgery scheduling and management
- Staff management system
- Human resource management system
- Doctor and nurse scheduling and shift management
- Reporting and analytics tools
- Patient portal for online access to medical records and appointment scheduling
- Integration with health insurance providers for claims management
- Mobile app for patients and healthcare providers
- System security and access controls.


## Run Locally

Clone the project:

```bash
  git clone 
```

Go to the project directory:

```bash
  cd ciniccare
```

Install the project dependencies using Composer:

```bash
  composer install
```

Create a copy of the .env.example file and rename it to .env:

```bash
  cp .env.example .env
```

Generate an application key:

```bash
  php artisan key:generate
```

Set up your database by editing the .env file and entering your database credentials.

Run database migrations:

```bash
  php artisan migrate
```

That's it! You've successfully installed a Laravel project from Git. You can now run the project locally by starting the development server using the command:

```bash
  php artisan serve
```

If you are using laragon then you can ignore artisan serve


## User Login

Email: admin@demo.com
Password: 12345678


## Author

- [@jahangir-alam-babu](https://www.github.com/jahangir-alam-babu)

