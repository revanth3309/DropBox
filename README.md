# EasyStore (Dropbox-Like File Storage)

EasyStore is a **cloud file storage** application inspired by Dropbox. It allows users to upload, manage, and share their files with ease. The application provides a **simple and intuitive interface** for users to interact with their files, upload new files, and view previously uploaded files.

### Key Features
- **File Upload**: Users can easily upload files from their local system.
- **File List**: A list of uploaded files is displayed with options to view file details.
- **Responsive UI**: Designed to work on different screen sizes, making it mobile-friendly.
- **File Storage**: Files are securely stored on the server with the option to scale for cloud storage.
- **Simple and Clean Interface**: The UI is clean and easy to use, making it suitable for both casual and power users.

---

## How It Works

### Frontend (React)
The frontend of the application is built with **React** and provides a user-friendly interface where users can upload files, see a list of their uploaded files, and manage them.

- **File Upload**: The user selects a file from their local system, and the file is uploaded to the backend server. The user is notified if the upload is successful or not.
- **File List**: After uploading a file, the file is listed with its name and details. Users can manage these files in the future.
- **Responsive Design**: The UI is designed to look great on any device, from mobile phones to desktop screens.

### Backend (Flask & SQLite)
The backend is built using **Python Flask** and an **SQLite database** for storing information about the uploaded files.

- **File Storage**: The files are saved on the server in a designated folder.
- **Database**: The backend keeps track of all the uploaded files in a database, storing metadata like file names, sizes, and paths.
- **File Deletion**: Users can delete uploaded files, both from the database and the storage system.


