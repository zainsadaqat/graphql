# GraphQL

- GraphQL is a query language that gives client the power to ask for what exactly they need 
- GraphQL prevents Over Fetching and Under Fetching
 
 
> Over Fetching means, GraphQL prevents fetching unnecessary data
```js
Query {
 type Products {
   name
   image
 }
}
```

> Under Fetching means, GraphQL supports fetching data from multiple endpoints at the same time

```js
Query {
 type Category(id:1) {
  type Products {
    name
    image
   }
 }
}
```
