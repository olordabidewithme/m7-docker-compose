Demo Project
Docker Compose - Run multiple Docker containers
Technologies used:
Docker, MongoDB, MongoExpress
Project Description:
Write Docker Compose file to run MongoDB and MongoExpress containers.

Step 1 : Start MongoDB and Mongo Express
```bash
docker-compose -f docker-compose.yaml up
```

Step 2 : Open Mongo Express UI
```bash
http://localhost:3000
```

Step 5 : Create a new database "user-account"

Step 6 : Create a new collection "users"

Step 7 : Start Node Server
```bash
cd app
npm install
node server.js
```
Step 8: Access Nodejs Application
```bash
http://localhost:3000
```
