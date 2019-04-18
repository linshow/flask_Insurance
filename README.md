# Flask_Blog_System
A blog system written in flask that I developed when I study flask

## Local Run

  [Python 3+](https://www.python.org/downloads/) need be installed

  ```
  pip install -r requirements.txt
  ```
  
  ```bash	
  python manage.py runserver
  ```
  Navigate to http://127.0.0.1:5000, and then use xx@xx.com/xx to login.

## Docker Run

  ```bash	
  docker pull luislu/microblog
  docker run -d -p 5000:5000 luislu/microblog
  ```
  Navigate to http://127.0.0.1:5000, and then use xx@xx.com/xx to login.

## Contents

  - **Complete user authentication(Register,Email Verification,Login,Forget/Reset Password)**
  ![alt text](https://github.com/luisxiaomai/Images/blob/master/Flask_Study_App/login.png)

  
  - **Simple Blog System** 
  ![alt text](https://github.com/luisxiaomai/Images/blob/master/Flask_Study_App/Blog_Lite.png)
  
  - **RichText Editor** 
  ![alt text](https://github.com/luisxiaomai/Images/blob/master/Flask_Study_App/editor.png)
  
  - **Markdown Editor** 
  ![alt text](https://github.com/luisxiaomai/Images/blob/master/Flask_Study_App/comments.png)
  

 

