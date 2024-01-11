dynamic nodejs app with dynamodb
----------------------------------------------------

yum install git -y 

git init 

git pull https://github.com/BSBiradar/Nodejswebapps.git
----------------------------------------------------
cd dynamic-website-with-dynamodb 

yum install nodejs -y 

npm install 

npm install pm2@latest -g 

pm2 start app.js 

pm2 logs

then go to chrome check with :  http://(ipaddr):3000
your application is visible to you

other pm2 commands

pm2 stop all

node app.js

pm2 restart all

pm2 status

pm2 restart app.js 
