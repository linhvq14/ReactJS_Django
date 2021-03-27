 ReactJS_Django
-----
Setting up
-----
Step 1 — Setting Up the Backend:
-----
#### - Create and activate environments:
#####    + Open terminal in your project and run:
    python -m venv .env
#####    + Next:
    cd .env/Scripts

    activate
#### - Install library and run backed server:
#####    + Back to ReactJS_Django folder and run:
    python install -r requirements.txt

    cd backend

    python manage.py makemigrations

    python manage.py migrate

    python manage.py runserver
 
###Step 2 — Setting Up the Frontend:
#### - Install module:
#####    + Open another terminal in your project and run:
    cd frontend

    npm install bootstrap@4.6.0 reactstrap@8.9.0 --legacy-peer-deps

    npm install axios@0.21.1

    npm start
