# Shared Document Dashboard

This is a document management system built with **Streamlit** and **SQLite**. It allows users to upload, search, filter, replace, and delete documents shared across a small group of users.

## Features

- **User Authentication**: Only 5 users with valid credentials can access the system.
- **File Upload**: Users can upload documents which are saved and shared with all users.
- **File Search & Filter**: Users can search and filter documents based on the filename and upload date.
- **File Replace**: Users can replace an existing document with a new one.
- **File Delete**: Users can delete files from the system.

## Technologies

- **Streamlit**: A Python framework used for building interactive web apps.
- **SQLite**: A lightweight database for storing file metadata.
- **Python**: The backend logic is written in Python.

## Installation

### Prerequisites

1. Python 3.8+  
2. Install required Python libraries:

```bash
pip install streamlit sqlite3
