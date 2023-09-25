npm i express express-graphql graphql mongoose cors colors

npm i -D nodemon dotenv

## Commits/Queries

### Commit '02. A single client request'
```
{
  client(id: 1) {
  id,
  name,
  email,
  phone
}
}
```

### Commit '03. Clients request'
```
{
  clients {
    id, name, email, phone
  }
}
```

### Commit '04. Project and projects requests'
```
{
  project(id: 1) {
    id, name, description, status
  }
}
```
```
 
```

### Commit '05. Projects and client inside of client and project req'

### Commit '06. Configure mongoose to fetch data from MongoDB'

### Commit '07. Add a client to MongoDB'

```
mutation {
  addClient(name: "Tony Stark", email: "ironman@gmail.com", phone: "955-365-3376") {
    id
    name
    email
    phone
  }
}
```