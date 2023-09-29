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

### Commit '08. Delete a client from MongoDB'

```
mutation {
  deleteClient(id: "paste_id_here") {
    id
    name
    email
    phone
  }
}
```

### Commit '09. Add a project to a MongoDB'

```
mutation {
  addProject(name: "Learn Node.js", description: "Blah", status: new, clientId: "6511734b230621b107d3bc0d") {
    id
    name
    description
    status
  }
}
```

### Commit '10. Delete and update a project from a MongoDB'
```
mutation {   
  deleteProject(id: "65118653c9fa7fb9348c018f") {
    id 
  }
}
```

```
mutation {   
  updateProject(id: "65171d0a5367cd612fda33bd", name: "Learn Node.js!!!") {
    id 
  }
}
```