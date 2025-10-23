# Character Query by ID

This directory contains GraphQL queries and outputs for fetching specific Rick and Morty characters by ID using the public Rick and Morty GraphQL API.

## Endpoint
https://rickandmortyapi.com/graphql

## Files
- `character-id-1.graphql` — Query for character ID 1  
- `character-id-1-output.json` — Output for character ID 1  
- `character-id-2.graphql` — Query for character ID 2  
- `character-id-2-output.json` — Output for character ID 2  
- `character-id-3.graphql` — Query for character ID 3  
- `character-id-3-output.json` — Output for character ID 3  
- `character-id-4.graphql` — Query for character ID 4  
- `character-id-4-output.json` — Output for character ID 4  

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
