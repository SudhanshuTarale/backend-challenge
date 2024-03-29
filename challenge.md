To run this project:

1. Clone repository using command: git clone https://github.com/SudhanshuTarale/backend-challenge
2. Database setup using python manage.py migrate 
3. Run migrations using python manage.py makemigrations
4. Create superuser using python manage.py createsuperuser and following the instructions in command line

Start the project

1. Start the project using python manage.py runserver
2. API's:
Tasks API:
List and Create Tasks: http://127.0.0.1:8000/api/tasks/
Retrieve, Update, and Delete Task: http://127.0.0.1:8000/api/tasks/<task_id>/

Label API:
List and Create Labels: http://127.0.0.1:8000/api/labels/
Retrieve, Update, and Delete Label: http://127.0.0.1:8000/api/labels/<label_id>/

There are laready 2 users created with is_staff True
1. username: "user1", password: "password1"
2. username: "user2", password: "password2"