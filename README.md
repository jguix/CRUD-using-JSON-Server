# CRUD-using-JSON-Server
command to run the server : npm start

The following HTTP endpoints are created automatically by JSON server:
* GET    /employees
* GET    /employees/{id}
* POST   /employees
* PUT    /employees/{id}
* PATCH  /employees/{id}
* DELETE /employees/{id}

If you make POST, PUT, PATCH or DELETE requests, changes will be automatically saved to db.json. A POST, PUT or PATCH request should include a "Content-Type: application/json" header to use the JSON in the request body. Otherwise it will result in a 200 OK but without changes being made to the data.

if you need a larger amount of data the manual way can be cumbersome. An easy solution to this problem is to use the Faker.js (https://github.com/marak/Faker.js/) library to generate fake data. 

npm install faker
read more on :https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d 

[Using middlewares](https://github.com/typicode/json-server/issues/453) 





###This code is based on below Blogs:
1. [create-a-rest-api-with-json-server](https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d)
2. [fast-prototyping-restangular-and-json-server](https://glebbahmutov.com/blog/fast-prototyping-restangular-and-json-server/)
3. [JSON-Server home site](https://github.com/typicode/json-server)


### Articles on JSON-server

* [Node Module Of The Week - json-server](http://nmotw.in/json-server/)
* [Mock up your REST API with JSON Server](http://www.betterpixels.co.uk/projects/2015/05/09/mock-up-your-rest-api-with-json-server/)
* [ng-admin: Add an AngularJS admin GUI to any RESTful API](http://marmelab.com/blog/2014/09/15/easy-backend-for-your-restful-api.html)
* [Fast prototyping using Restangular and Json-server](http://glebbahmutov.com/blog/fast-prototyping-using-restangular-and-json-server/)
* [Create a Mock REST API in Seconds for Prototyping your Frontend](https://coligo.io/create-mock-rest-api-with-json-server/)
* [No API? No Problem! Rapid Development via Mock APIs](https://medium.com/@housecor/rapid-development-via-mock-apis-e559087be066#.93d7w8oro)

