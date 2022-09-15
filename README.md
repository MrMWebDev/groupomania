# PROJECT 7 - OPENCLASSROOMS - WEB DEVELOPER

## Groupomania - Social Network

<h3>- Skills assessed :</h3>
<ul>
  <li>  Authenticate a user and maintain their session</li>
  <li>  Personalize the content sent to a web client</li>
  <li>  Manage data storage using SQL</li>
  <li>  Implement secure data storage using SQL</li>
</ul>

### - Technologies used :
NodeJs - VueJs - MySQL - Bootstrap - Sass
  
## INSTALLATION
### Prerequisites :
You must have installed on your machine :

<ul>
  <li> Git : https://git-scm.com/downloads</li>
  <li> Node.js : https://nodejs.org/en/</li>
  <li> MySql :  https://dev.mysql.com/downloads/installer/</li>
</ul>

Create an empty folder then clone this repository inside : 

```
git clone https://github.com/MrMWebDev/groupomania
```
## MySQL
In the groupomania/backend/.env file, put the password to access your database and your username if necessary (root by default)
```
DB_USER=root
DB_PASS=
```
Open MySql command Line client then perform these two command lines :
```
CREATE DATABASE groupomania;
USE groupomania;
```
Import the groupomania.sql file (which is at the root of the project) : 
```
source (path to groupomania.sql file);
```
Be careful to indicate the path with "/" and not "\".

## BACK END
Open a terminal in the backend folder then run the following command lines:
```
npm install
node server
```
## FRONT END
Open another terminal in the frontend folder then run the following command lines:
```
npm install
npm run serve
```

Open browser at http://localhost:8080/

### Features :
The site allows
<ul>
  <li>Share posts (with or without photos)</li>
  <li>Comment and like posts</li>
  <li>Personalize your profile (change profile picture, description, etc.)</li>
  <li>Modify and delete his account</li>
</ul>
