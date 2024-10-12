
![alt text](image.png)

![alt text](3.png)

## Installation
- **Linux/Mac**

1. Create and active virtual environment using  <br>
` virtualenv -p python3 env` <br>
` cd venv` <br>
`source bin/activate` <br>
2. Change the directory using <br>
`cd ..` <br>
` cd Complain_Management_System`<br>
3. Now you need to install python packages to run the app <br>
`pip3 install -r requirements.txt`
4. Migrations <br>
`python manage.py makemigrations`
`python manage.py migrate`
5. Run Django app <br>
`python manage.py runserver`


- **Windows**

1. Install and active virtual environment using  <br>
`pip install virtualenv` <br>
`virtualenv env` <br>
`env\Scripts\activate` <br>
2. Change the directory using <br>
` cd Complain_Management_System`<br>
3. Now you need to install python packages to run the app <br>
`pip3 install -r requirements.txt`
4. Migrations <br>
`python manage.py makemigrations`<br>
`python manage.py migrate --run-syncdb`
5. Run Django app <br>
`python manage.py runserver`
