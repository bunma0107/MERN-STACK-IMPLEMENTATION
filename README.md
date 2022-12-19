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

vim todo.js
vim api.js
![image](https://user-images.githubusercontent.com/113097621/207549790-e68e48b5-378c-45ce-a40b-8524e59a7c6f.png)

node index.js
![image](https://user-images.githubusercontent.com/113097621/207552425-431df0ac-82d8-4953-aaf8-064b980ac9e2.png)
![image](https://user-images.githubusercontent.com/113097621/207802077-297a27cb-6d82-437d-bf4c-d6bd50be217e.png)


To Open Postman, create a POST request to the API
![image](https://user-images.githubusercontent.com/113097621/208472574-c2ca2b08-4f1a-4c6d-9089-e45c4eed09df.png)




Running a React App
Install concurrently
![image](https://user-images.githubusercontent.com/113097621/208098410-143e5fff-ed74-4990-b577-647dcb0b2635.png)

Step 2 – Frontend creation
![image](https://user-images.githubusercontent.com/113097621/208476181-029d7257-c833-4b95-951a-38c6c0ee718a.png)

![image](https://user-images.githubusercontent.com/113097621/208476680-404969bb-e766-400c-b323-8ac256fc5f59.png)

Running a React App
![image](https://user-images.githubusercontent.com/113097621/208477118-45f71521-fbdc-43f8-80fc-f95e8dc1febb.png)

![image](https://user-images.githubusercontent.com/113097621/208477400-ce2fe623-96b2-4a0c-a82c-13ba9007822b.png)

npm run dev
![image](https://user-images.githubusercontent.com/113097621/208482974-e1e937e7-14ff-4cd4-adba-3dc7e9c38c0c.png)

cd client
![image](https://user-images.githubusercontent.com/113097621/208483955-6cd6d627-800e-424e-8d8e-768e9ee607f6.png)

Install Axios
![image](https://user-images.githubusercontent.com/113097621/208484153-33887691-3189-4918-8020-3d3264715220.png)


Go to ‘components’ directory
cd src/components

![image](https://user-images.githubusercontent.com/113097621/208488069-8cd11bff-2caf-4fb7-afa7-f97e2528c24c.png)

![image](https://user-images.githubusercontent.com/113097621/208488182-be1a8082-ce1f-40a6-9c46-70e2bf15feb0.png)

![image](https://user-images.githubusercontent.com/113097621/208488412-0b366f18-4d48-4d2b-92a2-b36d85378102.png)

![image](https://user-images.githubusercontent.com/113097621/208488297-06110e44-d34c-4393-ab63-7abd2addc2b2.png)




npm run dev
![image](https://user-images.githubusercontent.com/113097621/208486880-b424218c-8c17-420f-8363-6cfb6db161fa.png)







