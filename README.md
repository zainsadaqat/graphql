# GraphQL  

- Apollo Client 
- NodeJS    
  
   
## Server Side 
● Type Definitions
● Resolvers
● Query Definitions
● Mutation Definitions
● Composition
● Schema
 
## Client Side
● Queries
● Mutations
● Fragments

## Creating a Schema
● Using Schema Definition Language (SDL)
● Programmatically Creating a Schema using language
constructs

## Basic parts
● Types - a construct defining a shape with fields

● Fields - keys on a Type that have a name and a value type

● Scalars - primitive value type built into GraphQL

● Query - type that defines how clients can access data

● Mutation- type that defines how clients can modify or
create data


## What is a Query?
A Type on a Schema that defines operations clients can
perform to access data that resembles the shape of the other
Types in the Schema

## Creating Queries
● Create Query Type in the Schema using SDL

● Add fields to the Query Type

● Create Resolvers that for the fields

> GraphQL is a strongly typed Query Language if any condition doesn't satisfy. It's gonna break.

After creating a Type, the next step is to create a query like how can someone access this query.
