##https://discord.gg/zDhzk7Cs4D
## how-to-set-up-gamesense-website
If you just want to set up ur gs site for free, here is how:
*   You will need to have an account at : https://www.000webhost.com/, if you don't, just sign up for one
![image](https://user-images.githubusercontent.com/106918352/230726359-18ed4739-b4a3-44f5-b2cf-fcac13607a05.png)
Name your website whatever you want, after that refresh the page
Then click on manage website ---> file manager
Now go to public_html and delete everthing in there

Next download this: https://github.com/JamalHackCOM/gamesense-forum

To upload the files, just simply CTRL+A , drag and drop them to the file manager
![image](https://user-images.githubusercontent.com/106918352/230726768-4d6bd750-cc25-40bc-a453-f6c979874508.png)
While you are waiting for the uploading process to finish, head back to the site manager then go to Tools ---> Database manager
r

![image](https://user-images.githubusercontent.com/106918352/230726868-a714a53b-26b6-4064-882f-aaaf857f9e4f.png)

Click on New Database

![image](https://user-images.githubusercontent.com/106918352/230726876-068ea884-8697-45e0-a9d3-c7fd01af9a02.png)

Fill in the form
![image](https://user-images.githubusercontent.com/106918352/230726882-d073358f-8902-4725-baf8-698a4d2e551e.png)

Database name - choose any name you want 
Database username - choose any username you want 
Password - best to make it secure and random use some special characters in there
Now, once you’ve created the database it should appear like below and you’ll be able to manage, delete and change the password if you need to.
If you click the manage button a new page should open and you’ll be allowed into phpMyAdmin to access the database directly.

![image](https://user-images.githubusercontent.com/106918352/230726900-696f4320-6141-45e1-ad4e-0591f3268bf3.png)

Go to phpMyAdmin, click on Import then upload the "uploadthistoyourdatabase.sql" file. ( Make sure you are in your DBname or you will get error )

![image](https://user-images.githubusercontent.com/106918352/230727329-41027649-f31e-4f26-8af2-66598356784a.png)


When you are done uploading files , go to index.php in file manager, go to line 98 and change to domain to yours.

Then , set db info in forums/config.php

inside ur db go to "users" table and add a guest user

inside ur db go to "config" table and change all the domains to urs

inside ur db go to "codes" table and add a inv so you can register

You are now accessible to the website

![image](https://user-images.githubusercontent.com/106918352/230727555-22e3717e-5bf4-4e4c-bca9-86c3b8dd9bd7.png)








