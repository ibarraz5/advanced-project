# advanced-project


How to run the application

###check for local open port
    run cmd prompt as admin
    netstat -ab
    if port says LISTENING, it is an open port to use
###open new terminal
    cd server/
            install package.json and websocket
            npm init -y
            npm install ws
            npm install express
            nodemon install
make sure server is running so html client page can connect
run server by:
 go to server folder
 cd server/
 type nodemon index.js to run server

to open the chat go to http://localhost:9876/ on your webrowser 
you can also open an incognito webrowser window and open it there so you can connect as a different user

install the live server plugin by ritwick dey on visual studio code to run the application

click on the index.html file and click go live at the bottom

info
    css uses an online file with preset styling for containers, titles, buttons, etc
