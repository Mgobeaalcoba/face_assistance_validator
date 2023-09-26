# Face Verification & Access Control App

This repository contains an application that leverages facial recognition technology to grant or deny access to individuals based on their permission status. It also keeps a record of entries in a database for security and auditing purposes.

## Features

- **Facial Verification:** The app uses facial recognition to identify individuals.
- **Access Control:** Individuals are granted or denied access based on their permission status.
- **Database Recording:** All access attempts are logged in a database for security and auditing.
- **User-friendly Interface:** An intuitive interface makes it easy to use and manage access permissions.

## Technologies Used

- **Python:** The core programming language for the application.
- **OpenCV:** Used for facial recognition and image processing.
- **SQLite:** A lightweight database management system for storing access records.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/face-verification-access-control.git
   cd face-verification-access-control
   ```

2. Create a virtual environment (recommended):

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   En Windows:
   ```bash
   .\venv\Scripts\activate
   ```

   En Linux/Mac:
   ```bash
   source venv/bin/activate
   ```
   
4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the application:

   ```bash
   python main.py
   ```

