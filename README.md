# Easy-File-Sharing-API

## Overview

Easy-File-Sharing-API is a web application that allows users to easily upload and share files and directories. Upon uploading, a unique link is generated for downloading the shared files, which users can distribute to others. This app is built with Django Rest Framework, ensuring ease of maintenance and scalability. The app is designed to simplify file sharing, especially for large or multiple files, without requiring additional software or tools.

## Features

- **File Upload:** Users can upload files or entire directories through the app interface.
- **Unique Download Link:** Each uploaded file or directory is assigned a unique link for easy sharing and downloading.
- **Simple Sharing:** Once the file is uploaded, users can simply share the generated link with others, allowing them to download the content.
- **REST API:** The app is built using Django Rest Framework, providing a simple and efficient API for easy integration.

## Requirements

Before running the app, make sure you have the following installed:

- Python 3.8+
- Django 3.0+
- Django Rest Framework
- Any other dependencies listed in `requirements.txt`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ms-Ngari/FileSharingApp_REST_API.git
   cd FileSharingApp_REST_API
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up the database:
   ```bash
   python manage.py migrate
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

The application will be available at `http://127.0.0.1:8000`.

## Technologies Used

- **Django**: A high-level Python web framework.
- **Django Rest Framework**: A toolkit for building Web APIs.
- **SQLite/PostgreSQL/MySQL**: (depending on configuration) for storing file metadata.
- **Python**: The programming language used for the backend.

## Contributing

Contributions are welcome! If you’d like to contribute, please fork the repository, create a branch, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
