# thesis-management-system
Here's a sample `README.md` for your academic project management system:

---

# Academic Project Management System

## Overview
The **Academic Project Management System** is a Django-based web application designed to streamline the management of student projects and supervisor assignments. This system allows students to submit their projects, supervisors to manage and oversee multiple student projects, and administrators to maintain a well-organized database of academic activities.

## Features
- **Student Management**: Add, update, and delete student records.
- **Supervisor Management**: Assign supervisors to students, with the ability to manage multiple students.
- **Project Submission**: Students can submit project titles, abstracts, and full-text documents.
- **Academic Unit Classification**: Categorize students based on their academic units (e.g., Biochemistry, Industrial Chemistry).
- **Role-Based Access**: Different access levels for students, supervisors, and administrators.

## Technologies Used
- **Backend**: Django, Python
- **Database**: SQLite (default, easily switchable to PostgreSQL)
- **Frontend**: HTML5, CSS3, Bootstrap
- **File Storage**: Local file system for storing project documents
- **Version Control**: Git, GitHub

## Installation

### Prerequisites
- Python 3.8+
- Django 4.0+
- Git

### Setup Instructions
1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/academic-project-management.git
    cd academic-project-management
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply the migrations:**
    ```bash
    python manage.py migrate
    ```

5. **Run the development server:**
    ```bash
    python manage.py runserver
    ```
    Visit `http://127.0.0.1:8000/` in your browser to view the application.

## Usage

### Adding a Student
- Navigate to the student management page.
- Click "Add Student" and fill in the student's details, including their assigned supervisor and academic unit.

### Submitting a Project
- Students can log in and navigate to the "Submit Project" page.
- Fill in the project title, abstract, and upload the full project document.

### Managing Supervisors
- Admins can assign or reassign supervisors to students, ensuring proper oversight of each student's project.

## Screenshots
![Dashboard Screenshot](docs/screenshots/dashboard.png)
*Screenshot of the admin dashboard.*

![Project Submission Screenshot](docs/screenshots/project_submission.png)
*Screenshot of the project submission form.*

## Project Structure
```
academic-project-management/
├── academic_project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── projects/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── students/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── supervisors/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── templates/
├── manage.py
├── README.md
└── requirements.txt
```

## Contributing
Contributions are welcome! If you have suggestions or would like to report an issue, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or issues, please contact [yourname@domain.com](mailto:yourname@domain.com).

---
