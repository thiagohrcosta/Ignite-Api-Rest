![enter image description here](https://camo.githubusercontent.com/c1961440b3cd295d2e75cbe71c7177fb4474f5eb8cbe53e359b112e4128723ac/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f646c6f6164623262782f696d6167652f75706c6f61642f76313637343532333539362f34326531616238302d373761662d313165622d396530372d3437663965343662336536655f61786f636e6e2e706e67)

# Transaction API (NodeJS)
This project was developed during the Node.js specialization created by Rocketseat. It is a API only project that create, update, destroy and list a summary of transactions built in NodeJs. 



## Technologies

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)

## Other Technologies
[Supertest](https://github.com/ladjs/supertest): This application has tests to check the requests. 

## Endpoints

Api Endpoint: https://ignite-transaction-api.onrender.com/

**List all user transaction**: 
GET: https://ignite-transaction-api.onrender.com/transactions
![enter image description here](https://res.cloudinary.com/dloadb2bx/image/upload/v1677423821/api1_edqotq.png)

SHOW: https://ignite-transaction-api.onrender.com/transactions/:id
![enter image description here](https://res.cloudinary.com/dloadb2bx/image/upload/v1677423904/api2_clprpz.png)

POST: https://ignite-transaction-api.onrender.com/transactions

    {
		"title": "Freelance",
		"amount": 3500,
		"type": "credit"
	}
![enter image description here](https://res.cloudinary.com/dloadb2bx/image/upload/v1677424004/api3_oi74zb.png)

**List the sum of all transacctions**
GET: https://ignite-transaction-api.onrender.com/transactions/summary
![enter image description here](https://res.cloudinary.com/dloadb2bx/image/upload/v1677424095/api4_missvp.png)

## How to run this application
To run this application in development environment after running ```npm install```, use the command ```npm run dev```, this command will run the script ```tsx watch src/server.ts```.   The server will running on port 3333. 