# Chat-Application
A chat application built with Django REST Framework, Django Signals, and React.js.

# Installation Process
To install this app please follow this below steps:
### Backend Setup
```
cd server/
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
```
### Frontend Setup
```
cd client/
npm install 
```
### Run the app
``` 
cd server/ 
python manage.py runserver
```
```
cd client/
npm start
```

Now you'll be redirected to `localhost:5173` Then open two browser window and do the signup with name, email, profile image and start chatting from two different window. 
