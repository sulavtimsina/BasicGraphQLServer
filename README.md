# BasicGraphQLServer
This GraphQL server is implemented using `apollo-server` and `graphql` node packages.

After cloning this project, run:
    `npm install`
A directory "node_modules" will be created at the root of the project.

Run the server using the following command:
       `node index.js`

When the server runs, open the server url in a browser and you will get the Graphiql Playground interface from where you can run graphql query.

Enter the following in the playground:
    `query {
  hello
}`

Click on the Execute button. You will get the following output:
    `{
  "data": {
    "hello": "world"
  }
}`
