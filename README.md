Let Folder-Nmae=Waquar

#git init,git status
-----------------------------------------
#setup Explianation  
-----------------------------------------
Waquar>python -m venv env

Waquar>cd env/Scripts

#Create virtual environment use any method u like OR use method written below

Waquar\env\scripts> Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned  

Waquar\env\Scripts>.\activate

#virtual environment activited. {env}

{env} Waquar\venv\Scripts>

#install django
----------------------

{env} Waquar>pip install django

#start project Name Edvanta
--------------------------
{env} Waquar>django-admin startproject Edvanta.

{env} Waquar>cd Edvanta

{env} Waquar\Edvanta>

#start app name crud app
----------------------------------------
{env} Waquar\Edvanta>django-admin startapp CRUD_APP

#create model for databse

{env} Waquar\Edvanta>py manage.py makemigrations

{env} Waquar\Edvanta>py manage.py migrate

#createsuperuser

{env} Waquar\Edvanta>py manage.py createsuperuser

{env} Waquar\Edvanta>py manage.py runserver

click on link-->http://127.0.0.1:8000/ to visit website 

------------------------------------------------
#push code ino gihub
------------------------------------------------
git add .

git commit -m 'changes commited'

git branch -M main

git remote add origin http

git push -u origin main





![Djago-crud — Mozilla Firefox 24-02-2024 16_02_05](https://github.com/waquar-az/Djano_CRUD/assets/106869966/74c6b0d4-e16c-4d2f-86b6-eb2c822c4a5c)

![Djago-crud — Mozilla Firefox 24-02-2024 16_02_21](https://github.com/waquar-az/Djano_CRUD/assets/106869966/073c2457-a632-428d-8108-7afbb162c65b)


![Djago-crud — Mozilla Firefox 24-02-2024 15_58_24](https://github.com/waquar-az/Djano_CRUD/assets/106869966/1ce32f61-c7ee-4ffb-ba8f-1ec55f0735ac)


![Djago-crud — Mozilla Firefox 24-02-2024 16_07_40](https://github.com/waquar-az/Djano_CRUD/assets/106869966/dcbfe8b3-dd1d-452c-956c-8810379ee92d)
