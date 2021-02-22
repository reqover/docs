## Reqover

Reqover is language agnostic tool that gives a picture about coverage of APIs based on Open API (Swagger).

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

[![Deploy to DO](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/reqover/docs/tree/master)

### Usage example:

For basic exmple you can user https://petstore.swagger.io

```
docker run -p 3000:3000 \
-e API_SERVICE_URL='https://petstore.swagger.io' \
-e SWAGGER_SPEC_URL='https://petstore.swagger.io/v2/swagger.json' \
spirogov/swagger-coverage
```

```
curl --location --request GET 'http://localhost:3000/v2/pet/9222968140497128105'
```

Open your browser:

```
http://localhost:3000/report
```

[Watch video](http://www.youtube.com/watch?v=YlAOJg_WGr4)

Report example:

![Swagger Coverage Report](.github/cov.png)
