# Webhooks_microservice
This project requires CLI and Postman to test. 
## Step 1. Clone the project and change the directory to Webhooks_microservice with following commands:
- git clone "https://github.com/shivankar27-b/Webhooks_microservice"
- cd Webhooks_microservice/
## Step 2. Install the dependencies using:
npm install
## Step 3. Then run the server using:
node index.js
## Step 4. Enter the following URLS for desired operation in POSTMAN:
- GET REQUEST: 
localhost:3000/webhooks/list
- POST REQUEST:
localhost:3000/webhooks/register
- UPDATE
"localhost:3000/webhooks/update/<id>
- DELETE
localhost:3000/webhooks/delete/<id>
- Trigger:
Localhost:3000/webhooks/ip
## Step 5. Check on browser using link: http://localhost:3000/webhooks/list
