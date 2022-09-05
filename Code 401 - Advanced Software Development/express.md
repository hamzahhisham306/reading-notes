# Reading Notes

1. What's the difference between PUT and PATCH?

- PUT HTTP Request: PUT is a method of modifying resources where the client sends data that updates the entire resource. PUT is similar to POST in that it can create resources, but it does so when there is a defined URL wherein PUT replaces the entire resource if it exists or creates new if it does not exist.

For example, When you want to update the Candidate name and email, you have to send all the parameters of the Candidate including those not to be updated in the request body, otherwise, it will simply replace the entire resource with the name and email.

- PATCH HTTP Request: Unlike PUT Request, PATCH does partial update e.g. Fields that need to be updated by the client, only that field is updated without modifying the other field.



2. Provide links to 3 services or tools that allow you to "mock" an API for development like json-server?
  - [MockServer](https://www.mock-server.com/)
  - [Postman](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/)
  - [Mockable](https://www.mockable.io/)
  
3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

 - Swagger allows you define the range of responses as 1XX, 2XX, ...5XX. If you provide the explicit code (i.e. 404) that will take precedence over the blanket request (in this case 4XX). Each response status requires a description. API specs do not necessarily need to cover all possible codes, but known error codes like 404 must be addressed.

 - APIDOC.js you can also define the errors in groups, if you do not provide the specific code the default error Error 4xx is thrown. You can set the title and description of the errror with @apiDefine

4. Compare and contrast SOAP and ReST?

SOAP (Simple Object Access Protocol) SOAP uses XML data in request/response messages, relying on XML Schema and other technology to enforce/parse structure of messages. It is platform indepedent (i.e. clients can use from disparate OS). SOAP is extensible, neutral, and independent of specific programming models.

REST (Representational State Transfer) Standard software architecture for web services. This is a webservice that provides it's web services in a text form allowing them to be read and modified with a stateless protocol and predefined operations. Common, stateless protocols allow for operability amongs disparate OS.

REST has become the more popular communication protocol. REST accesses data whereas SOAP performs operations by a standardized set of messaging patterns. Each are scalable and either can be used to achieve most outcomes. Benefits to REST include: not restricted to XML formatting, JSON is faster and provides a uniform base for transferring data to browser clietns, used by major services like Google, generally faster. Since either can be used to acheive the same results, the preference is up to the developer with the ultimate end goal in mind. SOAP can be preferable due to more robust security guarantees, built in logic to handle failed communications, and a set of standardized processes that make it easier to implement across firewalls/proxies without needing to modify the protocols themselves.

5. Document the following Vocabulary Terms
- Web Server:System of one or more computers that accepts incoming HTTP requests and sends corresponding HTTP responses; primary function is to deliver web contents/resources to the client (requestor). "Web Server" can refer to the hardware (computer storing web resources and software) or the software itself(that controls how users interact with hosted files, minimum functionality HTTP)

- Express: Express is a Node framework that simplifies HTTP verbs and allows for concise creation of HTTP verb handlers, simple integration with different view engines (i.e. porting information into front end templates), creates common settings such as port to use for connecting, and allows for additional request processing (middleware) to be inserted into request handling. It is unopinionated, meaning that you can structure it in various ways and use many different middleware options in myriad configurations.

- Routing: Open source runtime environment allowing for developers to create server side applications in JavaScript

- WRRC:This is how information flows through a web app: client opens brower/enters url, request gets sent to the server which takes the url request, server follows it's routing to serve back the requested web document and passes it to the view, the view renders the information in the desired format back to the client in their browser

6. Which 3 things had you heard about previously and now have better clarity on?
   - http request 
   - react life cycle
   - API
7. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
   - Express And NodeJs
   - TDD
   - data structure
9. What are you most excited about trying to implement or see how it works?
  EveryThing Hh
