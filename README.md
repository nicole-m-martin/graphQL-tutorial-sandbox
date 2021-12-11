Learning about GraphQL

# GraphQL

> A query language for your API

- QL means query language
- A server-side runtime for executing queries using a type system you define for your data.
- Used to load data from a server to a client, a way to get data from an API into your app.
- It is neither frontend or backend, but the language spoken between the two to exchange info.
- GraphQL is typed, meaning what you ask for is what you get back.

## Differences between REST and GraphQL:

- **GraphQL** exchanges data at a single endpoint. **REST** often involves several endpoints.
- In **GraphQL**, you can send queries to get exactly the data you're looking for in one request.
- A key difference is that with **GraphQL**, you which objects and data you have available with each query, so you can specify the **shape of the data** you want back from the server.
- With **REST** you can't really define what is returned to you, as the server decides this.

## Key Benefits of GraphQL:

1. **SINGLE ENDPOINT**: All data exchange is preformed at a single endpoint. If one of the resolver fails, the rest of the query can still resolve and return useful data.

2. **QUERY LANGUAGE**: You can declare which schemas you want the data from, and the format of the data, that prevents overfetching and underfetching of the data.

3. **GraphQL CLient Libraries**: Native integration with React framework and other client libraries considerably increases productivity for devs.
