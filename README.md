# Portfolio
This project is intended to develop Portfolio app to show case my skills.

# Tech Stack
Front End: HTML, CSS, Javacript, ReactJS

Back End: NodeJS, ExpressJS

Database: MongoDB

# MongoDB Setup
* MongoDB Server and MongoDB Client Setup and set in system environment variable

  MongoDB Sever: https://www.mongodb.com/try/download/community

  MongoDB Client: https://www.mongodb.com/try/download/shell?jmp=docs
* Test on cmd
  ```
  mongod --version
  ```
  ```
  mongosh --version
  ```
# Execution Flow
* Create database
```
use portfolio
```
* Create collection
```
db.createCollection("skills")
```
* Insert document
```
db.skills.insertOne({
  id: "1",
  name: "mongodb",
  stream: "database"
 })
```
* find document
```
db.skills.find()
```
