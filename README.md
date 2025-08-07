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
# MongoDB Operations
* Connect MongoDB server using MongoDB client
```
mongosh
```
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
* Find document
```
db.skills.find()
```
* Update document
```
db.skills.updateOne({ name: 'mongodb' }, { $set: { name: 'mysql' } }
)
```
* Delete document
```
db.skills.deleteOne({ stream: 'database' })

```

I am lerning  by html tables forms
example my and my friends data gather the html code 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>table</title>
</head>
<body>

 <table  border = "1">
    <th>id</th>
    <th>name</th>
    <th>phone</th>
    <th>mail</th>
    <th>address</th>
  <tr>
    <th>1</th>
    <th>gkreddymaram</th>
    <th>9121943891</th>
    <th>gopalkrishnareddymaram@gmail.com</th>
    <th>tellabadu</th>

</tr>
   <tr>
    <th>2</th>
    <th>venkatakrishna</th>
    <th>8074774594</th>
    <th>venkatakrishna@gmail.com</th>
    <th>west kombalapadu</th>

</tr>
        <tr>
    <th>3</th>
    <th>mallikarjunareddy</th>
    <th> 9014363971 </th>
    <th>mallikarjunareddy@gmail.com</th>
    <th>donakonda</th>

</tr>
    
    </tr>
    </th>
 </table>
    
    
</body>
</html>
