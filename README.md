I built an app to display information about the films in the Star Wars universe.

I use the [Star Wars API](https://swapi.dev/) to get the movie information for the application. This API uses REST services. And, unfortunately, that means you can’t access it using GraphQL.

Fortunately, though, there’s an open-source project for this! The [SWAPI GraphQL](https://github.com/graphql/swapi-graphql) wrapper uses GraphQL to access the Star Wars API.

You’ll find a SWAPI GraphQL folder which contains a pre-configured Node.js project that creates a local server. It then uses the SWAPI GraphQL wrapper to serve the information to your app using GraphQL.

To run the server, you need to make sure you have Node.js installed. If you don’t have it, visit Node.js for installation instructions.
