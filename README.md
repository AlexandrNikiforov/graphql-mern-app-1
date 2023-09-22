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

