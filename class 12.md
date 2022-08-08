# Reading Notes
  
## I have to understand these terms well in order to understand the way the library works and how to build web pages well

1. 100’s = > They typically inform the client that the header portion of the request has been received and that the server will attempt to meet the client's transmission request. such as switching to a different protocol or informing the 
  > client that their request will fail before they deliver the body
2. 200’s = > - It is a standard status code to inform a client that everything went well.
3. 300’s = > This redirect is used if there are multiple representations for one resource and the client (or its user) has to choose one of them.
4. 400’s = > The client error codes are as follows. They all concern erroneous requests that clients sent to servers. There are various reasons for this, including timeouts, incorrect URIs, a lack of authentication,
5. 500’s = > signifies Internal Server Error, which might signify anything from a third-party service that the backend tried to call to a missing header field that the backend accessed without verifying its presence.

6. What is a status code 202? 
   > If the deletion is asynchronous and takes some time, which is the case in distributed systems, it can be appropriate to return this code with some information or URL to tell the client when it will be deleted.

7. What is a status code 308?
   > This instructs the user to change from using the current URL to a different one in order to access the resource.

8. What code would you use if an update didn’t return data to a client?
   > 204 

9. What code would you use if a resource used to exist but no longer does?
   > 410 

10. What is the ‘Forbidden’ status code?
   > 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.


11. Why do we need to pull your MongoDB database string out of our server and put it into our .env?
   > due to the fact that when we deploy our program, we'll want to utilize anything other than our local host, and we need to conceal it for security.

12. What is middleware?
   > code that executes when a request is received by the server but before it is given to your routes.

13. What does app.use(express.json()) do?
   > It parses incoming JSON requests and puts the parsed data in req.

14. What does the /:id mean in a route?
   > oute parameters are named URL segments that are used to capture the values specified at their position in the URL. The captured values are populated in the req.params object, with the name of the route parameter specified in the path 
   > as their respective keys.

15. What is the difference between PUT and PATCH?
   > PUT is a method of modifying resource where the client sends data that updates the entire resource.
   > PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire date.

16. How do you make a default value in a schema?
   > your schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in.

17. What does a 500 error status code mean?
   > means Internal Server Error, which can be anything from a missing header field the backend accessed without checking its existence to an unreachable third party service the backend wanted to call.
 
18. What is the difference between a status 200 and a status 201? 
   > 200 that the request was received and understood and is being processed.
   > 201 status code indicates that a request was successful and as a result, a resource has been created.

 ## Things I want to know more about
