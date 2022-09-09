# lws-json-server-transactions

Example in memory todos api with json-server by Learn with Sumit

# Installation

```bash
git clone git@github.com:learnwithsumit/lws-json-server-transactions.git
cd lws-json-server-transactions
npm install json-server
npm start
```

Now opens:

- http://localhost:9000

You now have a full REST API. Test with POSTMAN or any other REST Client):

Retrieve all (GET):

```bash
GET http://localhost:9000/transactions
```

Retrieve one (GET):

```bash
GET http://localhost:9000/transactions/1
```

Post a todo (POST):

```bash
POST http://localhost:9000/transactions
```

Update todo (PUT):

```bash
PUT http://localhost:9000/transactions/3
```

Delete todo (DELETE):

```bash
DELETE http://localhost:9000/transactions/1
```


# Links

- https://github.com/typicode/json-server
- Jswon view Chrome plugin: https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc
- Learn with Sumit official website: htts://learnwithsumit.com