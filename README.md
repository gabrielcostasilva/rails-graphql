# RAILS & GRAPHQL
This project shows how to join Rails and GraphQL by following [_Using GraphQL with Ruby on Rails_ tutorial](https://www.apollographql.com/blog/using-graphql-with-ruby-on-rails).

> One can follow along the entire process by checking out each commit in this project.

## Project Overview
This project has two models: 
- _Item_, which consists of songs with: `title`, `description`, `artist`, and `image` (URL - not used);
- _Artist_, which consists of `email`, `first_name`, `last_name` and a computed `full_name`. 

One can use the `graphiql` browser to query items.