# insta-clone

>[EssyMwangi](https://github.com/EssyMwangi) 

# Description  
This is a clone of  Instagram where people share their  images and videos for other users to view. 
Users can sign up, login, view and post photos, search and follow other users.

## Screenshots 
###### Home page
 
<img src="">

###### user profile
 <img src=""> 

## User Story  
* Sign in to the application to start using. 
* Upload a pictures to the application. 
* Search for different users using their usernames.  
* See your profile with all your pictures.  
* Follow other users and see their pictures on my timeline.  

## Setup and Installation  
To get the project .......  
##### Cloning the repository:  
 ```bash 
https://github.com/EssyMwangi/insta-clone
```
##### Navigate into the folder and install requirements  
 ```bash 
cd insta-clone pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv virtual - source virtual/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations instagram
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 