http://localhost:8080/graphiql?path=/graphql  -- localhost endpoint


// Query to verify
query bookDetails {
bookById(id: "book-1") {
id
name
pageCount
author {
id
firstName
lastName
}
}
}