# A Journey to GraphQL

This project contains the presentation for my talk about TV 2s jurney to GraphQL, whay we have learned and the motivations for moving to GraphQL.

## Talk Abstract

TV 2 is a commercial broadcasting station based in Denmark. Beside traditional broadcasting TV we also run a video streaming service called TV 2 PLAY which serves both video on-demand and TV 2s own live channels.

Based on TV 2 PLAY I will be talking about our journey from REST based APIs to a GraphQL API, our motivation for doing so, and what we have learned.

In the talk I will:

* briefly talk about the history of TV 2 PLAY form monolith to microservices and our motivation for making that decision.
* describe the issues we were facing with a REST API and why it wasn’t a good fit for us.
introduce some context by showing how the current architecture of TV 2 PLAY looks today.
* talk about why we chose to change to a GraphQL API, what problems it solves for us and some of the problems we have run into.
* briefly touch on the anatomy of GraphQL vs. REST.
* demo a simple GraphQL application with downstream services and how to query the API.