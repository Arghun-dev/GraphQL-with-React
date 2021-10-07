# GraphQL-with-React

query we write to go from a user to friends company name
```js
query {
  user(id: 23) {
     friends {
        company {
          name
        }
     }
  }
}
```
