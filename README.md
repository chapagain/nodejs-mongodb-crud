Node.js, Express & MongoDB: Simple Add, Edit, Delete, View (CRUD)
========

A simple and basic CRUD application (Create, Read, Update, Delete) using Node.js, Express, MongoDB & EJS Templating Engine.

**Start MongoDB server**

```
sudo service mongod start
```

**Check MongoDB server status**

```
sudo service mongod status
```

**Go to MongoDB shell**

```
mongod
```

**Show databases**

```
show dbs
```

**Create database named "test"**

```
use test
```

**Create collection(table) named "users"**

```
> db.users.insert({name:"Mukesh Chapagain", age:88, email:"mukesh@example.com"})
> db.users.insert({name:"Raju Sharma", age:77, email:"raju@example.com"})
> db.users.insert({name:"Krishna Yadav", age:65, email:"krishna@example.com"})
```
