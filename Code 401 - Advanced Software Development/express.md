# Reading Notes

1. What's the difference between PUT and PATCH?

- PUT HTTP Request: PUT is a method of modifying resources where the client sends data that updates the entire resource. PUT is similar to POST in that it can create resources, but it does so when there is a defined URL wherein PUT replaces the entire resource if it exists or creates new if it does not exist.

For example, When you want to update the Candidate name and email, you have to send all the parameters of the Candidate including those not to be updated in the request body, otherwise, it will simply replace the entire resource with the name and email.

{
  id: 8,
  email: "lindsay.ferguson@reqres.in",

  // field to be updated
  first_name: "Lindsay",

  // field to be updated
  last_name: "Ferguson",
  avatar: "https://reqres.in/img/faces/8-image.jpg"
}

- PATCH HTTP Request: Unlike PUT Request, PATCH does partial update e.g. Fields that need to be updated by the client, only that field is updated without modifying the other field.

So in the previous example, we have to send only the name and email field in the request body.

{
"first_name":"Geeky",    // field that to be updated
"email":"hello@geeky.com",     // field that to be updated
}

2. Provide links to 3 services or tools that allow you to "mock" an API for development like json-server?
  - [MockServer](https://www.mock-server.com/)
  - [Postman](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/)
  - [Mockable](https://www.mockable.io/)
  
3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?



4.Compare and contrast SOAP and ReST?
