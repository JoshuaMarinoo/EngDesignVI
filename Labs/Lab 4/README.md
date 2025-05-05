
# CPE 322
## Lab 4: Django and Flask
### Instructions:
![image](https://github.com/user-attachments/assets/3ab6964f-86b5-408e-94ac-40bc503efe9b)


# Django Project
---

## Downloading Djnago and Django Rest Framework and other packages
![image](https://github.com/user-attachments/assets/1208fb07-8ef3-4d58-b30a-94d3380d9b92)
Downloading Both django and rest framework
Other packages:
setuptools
django-filter
markdown
requests

---

## Creating the stevens project and my app
![image](https://github.com/user-attachments/assets/66bf45aa-6e14-42d0-bb87-05775581358f)

django-admin startproject stevens
Creates a new Django project skeleton
Stevens folder with core files
python manage.py startapp myapp
manage.py migrate
Initializes the database and creates a db.sqlite3 file 
Use sqlite for project
Applies Django's default migrations (user/auth tables, etc.)

---

## Editing setting.py
![image](https://github.com/user-attachments/assets/60ba8bbf-e8d9-4ebd-a9c1-37d79a382087)
cd into stevens from stevens to get to settings.py through notepad and adding an asterisk to ALLOWED_HOSTS and 'myapp' to INSTALLED_APPS

--- 
## Copying key files from IOT 
![image](https://github.com/user-attachments/assets/e0169510-778d-4a0b-bd00-4cd93c79835c)
We have to copy these so that the stevens project works, otherwise we would have to create these py files from scratch in order to implement the stevens project

## Getting the api key from google cloud console
I had to create an account and verify a payment method to get API key. Due to the API key being attached my account and card I will not be sharing it in this lab.
However I added the line <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script> replacing the YOUR_API_KEY" part with my API key in the index file 

---
## Copying static files
![image](https://github.com/user-attachments/assets/553cdde1-16c9-40d9-9de3-e47a755a86e2)

These files allow human computer interaction between a person and the webpage,fetches data from API, and affect visual styling of website.

---

## Configuration of app
![image](https://github.com/user-attachments/assets/9da7db29-ad31-4f43-b36d-a7fd521f8a6d)

Creates database migration files for your myapp app.
Applies all pending migrations to your database.
Creates an admin user for Django's admin interface.
I had problems with this but got it working. This wasr because during my copying steps i replaced view.py code with models.py code so I had to recopy view.py.

---

## Running server
![image](https://github.com/user-attachments/assets/41067693-4468-4ce0-ad01-1d74d2d5719b)
![image](https://github.com/user-attachments/assets/9f6ca38d-2513-4271-abdb-d8cf86070d20)
![image](https://github.com/user-attachments/assets/666cfdb1-3187-48a5-8516-7d467961cd72)
![image](https://github.com/user-attachments/assets/5e410bf4-d810-4561-9f14-94b5b9a69572)

Running the server, then logging in as admin and adding tempature data
The final app is shown there as well

---
# Django Rest Project

## Creating the mycpu project and my app
![image](https://github.com/user-attachments/assets/339de183-afe4-4ff6-8991-77028168d3d6)
![image](https://github.com/user-attachments/assets/c71add28-02a9-4dc6-a810-05d8ca767314)
![image](https://github.com/user-attachments/assets/2281d381-6acf-46c7-b16e-f6ab5d650667)


django-admin startproject mycpu
Creates a new Django project skeleton
mycpu folder with core files
python manage.py startapp myapp
manage.py migrate
Initializes the database and creates a db.sqlite3 file 
Use sqlite for project
Applies Django's default migrations (user/auth tables, etc.)
cd into stevens from stevens to get to settings.py through notepad and adding an asterisk to ALLOWED_HOSTS and 'myapp' to INSTALLED_APPS


--- 
## Copying key files from IOT 
![image](https://github.com/user-attachments/assets/73eda226-9996-48d7-9432-690882fa611b)

We have to copy these so that the stevens project works, otherwise we would have to create these py files from scratch in order to implement the stevens project

## Getting the api key from google cloud console
I had to create an account and verify a payment method to get API key. Due to the API key being attached my account and card I will not be sharing it in this lab.
However I added the line <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script> replacing the YOUR_API_KEY" part with my API key in the index file 

---
## Copying static files
![image](https://github.com/user-attachments/assets/d7064e30-9962-49c1-b0f7-9ea9bb69b9c9)

These files allow human computer interaction between a person and the webpage,fetches data from API, and affect visual styling of website.
Additionally copying controller.py and changing admin password

---

## Configuration of app
![image](https://github.com/user-attachments/assets/371df27c-145a-46b6-bd78-a9e84e8be811)
Creates database migration files for your myapp app.
Applies all pending migrations to your database.
Creates an admin user for Django's admin interface.


---

## Running server
![image](https://github.com/user-attachments/assets/d4f97cf7-c2bc-4f73-9710-2de0a8359a84)
![image](https://github.com/user-attachments/assets/1d964cab-0c14-45d9-b23b-b28d88ccdcf9)
![image](https://github.com/user-attachments/assets/6c4fb39c-4521-4548-a187-cd9c7e70e5b5)
![image](https://github.com/user-attachments/assets/1545ea38-d6b5-47cb-bafa-dac277842598)
![image](https://github.com/user-attachments/assets/17ada1ab-61e9-473d-9f2b-ff00f3fbb32a)
![image](https://github.com/user-attachments/assets/b42d8573-1306-4c84-b2ca-0539ce004119)


Running the server, then logging in as admin and adding location data
we also add
2024 to the Dt List at http://127.0.0.1:8000/dt
20 to the Cpu List at http://127.0.0.1:8000/cpu
20 to the Mem List at http://127.0.0.1:8000/mem
The final app is shown there as well

---

---
# Flask Project

## Install Flask
![image](https://github.com/user-attachments/assets/c5b0d167-887e-473a-a237-56dfb5c1b698)

--- 
## Running hello_world.py
![image](https://github.com/user-attachments/assets/d95c6315-a137-4927-bad3-d331387811a9)

## Summary
There was a lot of troubleshooting that needed to be done to get this lab, done however after the lab now I feel I have a much better grasp of using APIs, Django, Flask, and Django REST 

---
Author: Joshua Marino </br>
I pledge my honor that I have abided by the Stevens Honor System.

