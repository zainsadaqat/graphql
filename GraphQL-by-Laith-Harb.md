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

## Installation
```
npm isntall apollo-server graphql
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
> TypeDefs is a place where we define the structure of our data.

### Resolver
```
fruits: () => {
 return ["Oranges", "Mangoes"]
}
```

GraphQL has two types:
1. Scalar (String, Int, Float, Boolean, !, Array of Strings, Array of Booleans, Array of Int, Array of Floats)
2. Object (when we want to use multiple types at the same time) 

## Mutation  
   
   
