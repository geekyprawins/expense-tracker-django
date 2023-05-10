# Expense Tracker using Django, Postgres.
## Internet Technology  Lab Mini Project 2023

**Trackify Me** is a web-based expense-tracking application developed using the
Django web framework and PostgreSQL database. The application allows users to
track their expenses, income, categories, and budgets, and set financial goals. The
application was designed to be user-friendly and responsive, with a simple and
intuitive interface.

### Team Details:-
* [Praveen Varma](https://github.com/geekyprawins)
* [Yashwanth](https://github.com/yashwanth008)


[Project Report](https://github.com/geekyprawins/expense-tracker-django/blob/master/IT-Lab-MiniProject-Report.pdf)

[Presentation Slides](https://www.canva.com/design/DAFhI0QsQvY/EKtM6UM3MaPAvXOwEr9BeA/edit?utm_content=DAFhI0QsQvY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


## How To Execute

Before starting make sure you create a virtual environment and install necessary
dependencies.

```bash
# Create a virtual environment
python3 -m venv venv

# Activate virtual environment in Linux
source venv/bin/activate


# Activate virtual environment in Windows
venv\Scripts\bin\activate


#Install django in new env
pip install django

#steps in running the django app
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver PORT_NO

```