# graphql-playground-docker
Tiny Docker image for [graphql-playground](https://github.com/prismagraphql/graphql-playground) served by Golang.

# Usage
```docker run --name graphql-playground -d juriad/graphql-playground-docker```

# Environment Variables
### HOST
The GraphQL server hostname and port. Default: localhost:9000

### GRAPQL_HOST
The GraphQL endpoint url. Default: http://$HOST/graphql

### SUBSCRIPTION_HOST
The GraphQL subscriptions WebSocket endpoint url. Default: ws://$HOST/subscriptions

### THEME
Property to customize your color theme. Possible values: 'dark', 'light'. Default: dark

### TITLE
Property to customize title. Default: "GraphQL Playground"

### PORT
The GraphQL Playground serving port. Default: 8080
