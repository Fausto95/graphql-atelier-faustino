# Atelier graphql par Fautino Kialungila.

Si vous souhaitez réaliser cette atelier au sein de votre équipe, merci de contacter Faustino : faustino.kialungila@gmail.com

## Setup 

`npm install`

Accéder à la page : [](http://localhost:3000/graphiql)

Entrer les requêtes graphql suivante :

Pour la creation :

```graphql
mutation {
  createPerson(firstName: "Faustino", lastName:"kialungila") {
    firstName,
    lastName
  }
}
```

```graphql
{
  allPersons{
    firstName,
    lastName
  }
}
```

```graphql
{
  allPersons{
    firstName,
    lastName
  }
}
```