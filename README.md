## Reqover

Reqover is language agnostic tool that gives a picture about coverage of APIs based on Open API (Swagger) or GraphQL.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

[![Deploy to DO](https://www.deploytodo.com/do-btn-blue-ghost.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/reqover/docs/tree/main)

### Usage example:

For basic example you can use https://petstore.swagger.io

```
docker run -p 3000:3000 reqover/reqover:latest
```

Setup API URL, Swagger specification url and save

```
curl --location --request GET 'http://localhost:3000/v2/pet/9222968140497128105'
```

Open your browser:

```
http://localhost:3000/reqover/swagger/report
```

[Watch video](http://www.youtube.com/watch?v=YlAOJg_WGr4)

Report example:

![Swagger Coverage Report](.github/cov.png)
