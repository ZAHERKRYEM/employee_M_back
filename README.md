
```markdown
 Employee Management System 

 Overview

In this challenge, you are tasked with developing an Employee Management System that includes multiple features for managing companies, departments, and employees. The system allows users to perform Create, Read, Update, and Delete (CRUD) operations for each of these entities. Additionally, there will be a workflow to handle the onboarding process for new employees and a role-based access control system to ensure data security.

 Features

- **Employee Management**: Add, edit, and delete employee information.
- **Department Management**: Organize companies and their respective departments.
- **Access Control**: Role-based permissions (Admin, Employee, etc.) to protect data.
- **Employee Onboarding Workflow**: Process new employee onboarding in an organized and efficient manner.
- **Interactive User Interface**: A user-friendly design to facilitate management tasks.

 Live Demo

You can try the live demo of the Employee Management System at the following link:

[Demo - Employee Management System](https://employeemback.pythonanywhere.com/swagger/)


 Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ZAHERKRYEM/employee_M_back.git
   cd employee_M_back
   ```

2. **Set up a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the database**:
   - Open the `settings.py` file and enter your database connection details.

5. **Run migrations**:
   ```bash
   python manage.py migrate
   ```

6. **Run the server**:
   ```bash
   python manage.py runserver
   ```

7. **Access the application**:
   - Open your browser and navigate to `http://127.0.0.1:8000/`.

