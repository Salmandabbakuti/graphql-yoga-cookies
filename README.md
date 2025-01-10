# graphql-yoga-cookies

This project demonstrates how to set and get cookies in a GraphQL server using [graphql-yoga](https://the-guild.dev/graphql/yoga-server)

## Getting Started

```bash

# Install dependencies
npm install

# Start server
npm start

```

### Sample Queries

```graphql
mutation SetCookie {
  setCookie(name: "session", value: "eyjh.....")
}

query GetCookie {
  cookie(name: "session")
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
