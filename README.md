# Angular8CodesExamples create a angular CRUD using NODEJS and MONGO-DB
# Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

# Run the code using following command
open app in terminal use  :  ng serve --open
open api in seprate terminal : nodemon server

# hope u have had install mongoDb and node js
while facing issue in installing mongo can use the following link and steps as mentions below:-
"step1)
sudo npm install mongodb@latest

step2)
echo 'deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10gen' | sudo tee /etc/apt/sources.list.d/mongodb.list
deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10gen

step3)
sudo apt-get update

step4)
echo "deb http://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.0.list
deb http://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.0 multiverse

step5)
sudo apt-get install MongoDB

step6)
nodemon serve

hopefully, it solved the same error I am facing while working on Angular8 with Nodejs and using MongoDB as a database.

for fetching above steps I follow the following links:-
1)https://docs.mongodb.com/v3.0/tutorial/install-mongodb-on-debian/
2)https://stackoverflow.com/questions/28945921/e-unable-to-locate-package-mongodb-org.
3)https://stackoverflow.com/questions/34733340/mongodb-gpg-invalid-signatures
that's all .. :)


"
