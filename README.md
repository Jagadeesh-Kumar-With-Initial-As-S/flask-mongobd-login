# flask app using MongoDB and Cookies

Usage:
 - Install MongoDB (MongoDB)[https://www.mongodb.com/try/download/community]
 - Create DB in MongoDB as myUsers
 - Create UserLogin Collection
 - `pip3 install -r requirements.txt`
 - Add credentials in **app.py** file
 - `python3 app.py`

#### DESCRIPTION
This is a simple login system with flask which can connect to mongoDB server to save user credentials and it also creates cookie if user logged in and destroys it once user is logged out.

#### Pytho Modules Used

 - bcrypt
 - Flask
 - pymongo
