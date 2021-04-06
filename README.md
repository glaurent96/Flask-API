# Python Flask API

---
### Overview
This is a simple store API built with Flask, Flask-RESTful, Flask-JWT, and Flask-SQLAlchemy. It also uses the Heroku Postgres add-on as a database.

Live link: https://glaurent-python-flask-api.herokuapp.com/stores

---
### Installation
Clone my repo:
```bash
git clone https://github.com/glaurent96/Flask-API.git
```
---
### Demo

In order to demo the API, you first need to download Postman to send requests with a body to create a user and authenticate yourself. You will then have access to all the API endpoints.

Step 1: Register User
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI1.png)
Step 2: Authenticate User
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI2.png)
With this JWT access token you now have access to the locked get item by name endpoint listed below and can perform CRUD operations on items in the stores:

STORES:
POST /store/<name>: (Create a new store)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI3.png)
GET /store/<name>: (Get a store by name)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI4.png)
DEL /store/<name>: (Delete a store by name)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI5.png)
GET /stores: (Get a list of all the existing stores)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI6.png)
ITEMS:
POST /item/<name>: (Create a new item)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI7.png)
GET /item/<name>: (Get an item by name)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI8.png)
PUT /item/<name>: (Update an item by name)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI9.png)
DEL /item/<name>: (Delete an item by name)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI10.png)
GET /items: (Get a list of all the existing items in the store)
![alt text](https://raw.githubusercontent.com/glaurent96/Images/main/flaskAPIimgs/flaskAPI11.png)
