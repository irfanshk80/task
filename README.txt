Software Requirements:

1. Wamp/Lamp Server
2. Yii 1.1
3. git

Pulling repository/project from github:

1. install git if its not.
2. Using console go to the directory where your www directory is there for web hosting
3. cd /var/www/html for lamp and cd wamp\www for wamp
4. create a project directory with this command.
LInix:
$>mkdir task
Windows:
>md task
Now change directory with this command
>cd task
5. Initialize the git with this command
>git init
6. Add remote git connection with this command
>git remote add origin https://irfanshk80@bitbucket.org/irfanshk80/task.git
7. Now pull the project
>git pull origin master


Import Database:

1. Find the task.sql in task directory of the project.
2. First Login and Create Database in mysql with this command
>create database task;
3. Import database with this command with task.sql provided by me is in D: drive
>mysql -u root -p task < D:\task.sql
4. On prompting for the password enter the password.


Use this urls to access the Task List Web Application

1. http://localhost/task/index.php
2. Try to register with a Name, username and password
3. Try to login with username and password.
4. create a task (http://localhost/task/index.php/task/create)
5. manage a task (mark complete , delete task) (http://localhost/task/index.php/task/admin)
6. Clicking on link "mark complete" link will take you to a form to mark this task as complete.
7. check and uncheck the box to make the task complete and running. Same will be refleted in the grid.
8. Finally Logout.

:)))Enjoy the Task List WebApp :)))

Enjoy git update -2
