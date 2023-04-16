# BookCRUD

## Install Dependencies (Follow given Step )

### step-1
> Move to that folder/Location where you Want your project

### step-2
>open terminal on folder/location path


### step-3
>Run given command

```
git clone https://github.com/itzDM/BookCRUD.git .
```
### step-4
>Now move to api (manually or type below command)

```
cd api
```

### step-5
>Install dependency using below command 

```
npm install
```
### step-6

>Set your PORT NUMBER and Mongodb DataBase URI in .env file.  
> e.g PORT=300    
> MONGO_URI=mongodb://localhost:27017

### step-7
>Run given command to start you server

```
npm start
```

#### !!!!----------Finally Done -----------!!!!!!!!


## -------  API Endpoints  ---------

### Here we Use PORT= 300  and You can Use any API Request Application like Postman,ThunderClient etc.

### Check Your API Work or not.
```
http://localhost:300/
```
>Output (...Api is Running)

### Creates a new book in the collection..
> set  "POST" Request and pass title ,author,description data into body

```
http://localhost:300/books
```
### Retrieves a list of all books in the collection..
> set  "GET" Request

```
http://localhost:300/books
```
### Retrieves a specific book by ID..
> set  "GET" Request pass "Id" in url where bookId written

```
http://localhost:300/books/bookId
```
### Updates an existing book by ID..
> set  "PUT" Request and pass data what you want to change into body

```
http://localhost:300/books/bookId
```
### Deletes a book by ID..
> set  "DELETE" Request and pass "Id" in url where bookId written

```
http://localhost:300/books/bookId
```
