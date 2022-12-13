# PROJECT 3 MERN-STACK-IMPLEMENTATION
Step 1 – Backend Configuration
sudo apt update

Upgrade ubuntu

sudo apt upgrade

Get the location of Node.js software from Ubuntu repositories.
![image](https://user-images.githubusercontent.com/113097621/207333474-3a972675-abf3-4544-8bf5-ce56f4083842.png)

Install Node.js on the server
sudo apt-get install -y nodejs
![image](https://user-images.githubusercontent.com/113097621/207334840-c4aa7e34-3aef-4b0c-b0c8-83cfa8a4528a.png)


Verify the node installation
node -v 
npm -v 
![image](https://user-images.githubusercontent.com/113097621/207337682-7f0afbba-df3f-42f7-b486-8606fec37d36.png)

Application Code Setup
mkdir Todo

Change Diredtory to Todo

npm init
![image](https://user-images.githubusercontent.com/113097621/207340008-60f5283c-b233-4fb1-acce-ce44c41b045d.png)

ls to confirm that you have package.json file created.
![image](https://user-images.githubusercontent.com/113097621/207340729-436ad7e4-b2b9-4bdb-9fb4-9d25491778f1.png)

install npm
![image](https://user-images.githubusercontent.com/113097621/207395684-189501e5-b29b-41b4-aacb-fbcf622da780.png)

To Install dotenv
npm install dotenv

Start Server
node index.js
![image](https://user-images.githubusercontent.com/113097621/207397208-c5ef87fd-c494-4967-8b4a-e3773813ccf3.png)

![image](https://user-images.githubusercontent.com/113097621/207407968-90d9e447-144b-4937-a655-70f3f0a41aa8.png)

ROUTES
mkdir routes
cd routes
touch api.js
![image](https://user-images.githubusercontent.com/113097621/207408770-e37655c2-8e28-4499-893d-09e17ed1defd.png)

MODELS
npm install mongoose
![image](https://user-images.githubusercontent.com/113097621/207409952-ee85310c-7fbe-40bc-8153-a7d1fa221066.png)

Create a new folder models :
mkdir models
cd models
touch todo.js
![image](https://user-images.githubusercontent.com/113097621/207410534-c6d9ad4e-32cc-41e5-9b2f-c204c7f14264.png)








