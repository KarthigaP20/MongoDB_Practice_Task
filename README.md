# MongoDB Practice Task

This project contains basic MongoDB commands and operations used for practicing core database concepts like:

- Creating and switching databases
- Creating collections
- Inserting documents
- Updating data
- Deleting documents
- Viewing data

All commands were executed using the MongoDB shell (`mongosh`) with a local MongoDB setup.


## 🗂️ Database Used

- **Database Name**: `ecomDB`
- **Collection Name**: `products`


## 🧪 Basic Commands Practiced

- `use ecomDB` – Create or switch to a database  
- `db.createCollection("products")` – Create a collection  
- `db.products.insertOne(...)` – Insert one document  
- `db.products.insertMany(...)` – Insert multiple documents  
- `db.products.find()` – View all documents  
- `db.products.updateOne(...)` – Update a specific document  
- `db.products.updateMany(...)` – Update multiple documents  
- `db.products.deleteOne(...)` – Delete one document  
- `db.products.deleteMany(...)` – Delete multiple documents  
- `db.products.drop()` – Drop the entire collection  


## 📸 Screenshots

### 🟢 Starting mongosh shell
![mongosh Start](screenshots/ss_1.png)

### 📂 Using `ecomDB` database
![Use ecomDB](Screenshots/ss_2.png)

### 📁 Creating `products` collection
![Create Collection](Screenshots/ss_3.png)

### 📝 Inserting documents
![Insert Docs](Screenshots/ss_4.png)

### 🔍 Finding documents
![Find Docs](Screenshots/ss_5.png)

### ✏️ Updating data
![Update Docs](Screenshots/ss_6.png)

### 🗑️ Deleting data
![Delete Docs](Screenshots/ss_7.png)

### 🚮 Dropping collection
![Drop Collection](Screenshots/ss_8.png)

### ✅ Final check
![Final Check](Screenshots/ss_9.png)


## 📁 File Included

- `MongoDB_Practice_Task.txt` – Contains all commands used with simple explanations.



## ✅ Status

✔️ Completed basic MongoDB operations for practice.
