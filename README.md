## How to build and run the application, commands:

#### cd Advanced Project/server/
#### nodemon index.js  
#### //after running server the client can connect by:
 go to http://localhost:5040/ on your webrowser 
#### //REFRESH PAGE IN BROWSER
#### you can also open an incognito webrowser window and open http link there so you can connect as a different user
#### //IF PORT ERROR, check open ports for your computer and change the port number in the code from 5040 to another port #

Build the application:
#### check for local open port
   ##### run cmd prompt as admin
     netstat -ab
     if port says LISTENING, it is an open port to use
     current port is 5040, change it to an open port if application is not running because port is busy
#### open terminal
   ##### cd Advanced Project/server/
   ##### run commands: 
            npm init -y
            npm install ws
            npm install express
            nodemon install


