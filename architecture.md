
# Architecture


There is a middleware in python which talks to [GQL](https://www.gqlstandards.org/) and SQL from one side and to [GRAPHQL](https://graphql.org/) - RESTFUL from the other side.

This middleware could be serverless.

Now is implemented with [flask](https://flask.palletsprojects.com/en/1.1.x/) and [graphene](https://graphene-python.org/)

This middleware execute all the crud operations (in graphql terminology all query and mutations)


The middleware exposes the resources of different repositories (SQL, NOSQL) with only one single point of access.

