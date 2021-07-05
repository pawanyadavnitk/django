# Django Project
This project contains some simple apps built using django web framework.

## Installation
1. Download/clone the project
2. Install Python 3.8.5
3.  Install the dependancies using
    ```bash
    cd django_projects
    pip install -r requirements.txt
    ```
## Usage
Use the following commands to runs the project, then follow the instructions/urls provided in specific app sections.
```
python manage.py migrate
python manage.py runserver
```
## Apps in the project
### 1. hello
Greets hello to the user
```
urls:
/hello/: displays "Hello, world!"
/hello/username : displays "Hello, Username!"
```
Features used
- flexible url