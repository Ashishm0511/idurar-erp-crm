System Requirement 
------------------------------
NPM
Node.js
Mongodb Atlas for self hosted 
-----------------------------

Software requiremnets

Backened  = Node.js, Express.js, mongodb

Frontend  = React.js, Redux

/Installation Steps 
-------------------------------
/* Clone the repository */

git clone https://github.com/idurar/idurar-erp-crm.git
cd idurar-erp-crm

/MongoDB Setup
------------------------------

Configure Backend
------------------------------
Navigate to /backend directory.
Create a .env file.
Set DATABASE to your MongoDB URI.
Set NODE_ENV to development or production as needed.
 
Install Backened Dependencies
cd backend
npm install

Start the Backened server
npm run start

Configure frontend
---------------------------
Navigate to /frontend.
Create / edit the .env file in the frontend
Configure any environment variables.

Install Frontened Depencies
cd frontend
npm install

Run frontend server 
nmp run dev