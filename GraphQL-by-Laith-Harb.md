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
   name
  type Products {
    name
    image
   }
 }
}
```

## GraphQL Server
In order to create a GraphQL server, we need to specify two things: 
1. Schema (Type Definition)
2. Resolver

### Schema
It's a way how our data is gonna look like
```
fruits: [String]
```
### Resolver
```
fruits: () => {
 return ["Oranges", "Mangoes"]
}
```
