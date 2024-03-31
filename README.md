# Django Python Machine Test

## Introduction

This Django project is designed to manage clients, projects, and users in a system. It provides functionalities to register clients, fetch client information, edit/delete client information, add new projects for a client, and assign users to those projects. Additionally, users can retrieve projects assigned to them.

## Table of Contents

- [Entities](#entities)
- [Tasks](#tasks)
- [Considerations](#considerations)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Entities

1. **User**: Represents registered users in the system.
2. **Client**: Represents clients registered in the system.
3. **Project**: Represents projects associated with clients.

## Tasks

1. **Register a Client**: Ability to register a new client.
2. **Fetch Client Info**: Ability to fetch information about clients.
3. **Edit/Delete Client Info**: Ability to edit or delete client information.
4. **Add New Projects for a Client**: Ability to add new projects for a client and assign users to those projects.
5. **Retrieve Assigned Projects to Logged-in Users**: Ability for users to retrieve projects assigned to them.

## Considerations

1. The system can have many users.
2. The system can have many clients.
3. A client can have many projects.
4. A single project can be assigned to many users.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/UtkarshRH/project.git

2. **Navigate to the Project Directory:**

    ```
    cd your-repository
    ```

3. **Install Python Dependencies:**

    ```
    pip install -r requirements.txt
    ```

4. **Apply Migrations:**

    ```
    python manage.py migrate
    ```

5. **Create Superuser (Admin Account):**

    ```
    python manage.py createsuperuser
    ```

6. **Run the Django Development Server:**

    ```
    python manage.py runserver
    ```

7. **Access the Application:**

    Open a web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
