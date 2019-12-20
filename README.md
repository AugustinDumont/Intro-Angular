# Intro-Angular

## Syntax GRAPHQL pour obtenir login :

mutation Register($login: String!, $pass: String!){
registerWithBasic(target: {collection: JUNIOR, email: "mail@mail.com"}, login: $login, pass: $pass)
}

mutation Login($login: String!, $pass: String!){  
 loginWithBasic(login: $login, pass: $pass) {
token
}
}
