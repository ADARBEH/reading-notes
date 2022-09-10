## What's the difference between PUT and PATCH?
#### The difference between PUT and PATCH in REST API is that PUT handles updates by replacing the entire entity, while PATCH only updates the fields that you give it.

#### Provide links to 3 services or tools that allow you to "mock" an API for development like json-server
- #### https://mockapi.io/
- #### https://apimocha.com/
- #### https://mockoon.com/
 

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
#### Swagger allows you define the range of responses as 1XX, 2XX, ...5XX. If you provide the explicit code (i.e. 404) that will take precedence over the blanket request (in this case 4XX). Each response status requires a description. API specs do not necessarily need to cover all possible codes, but known error codes like 404 must be addressed.

#### APIDOC.js you can also define the errors in groups, if you do not provide the specific code the default error Error 4xx is thrown. You can set the title and description of the errror with @apiDefine

## Compare and contrast SOAP and ReST
 

#### REST and SOAP are 2 different approaches to online data transmission. Specifically, both define how to build application programming interfaces (APIs), which allow data to be communicated between web applications. Representational state transfer (REST) is a set of architectural principles.

#### Many legacy systems may still adhere to SOAP, while REST came later and is often viewed as a faster alternative in web-based scenarios. REST is a set of guidelines that offers flexible implementation, whereas SOAP is a protocol with specific requirements like XML messaging.

# Document the following Vocabulary Terms

 

- #### Web Server :  System of one or more computers that accepts incoming HTTP requests and sends corresponding HTTP responses; primary function is to deliver web contents/resources to the client (requestor). "Web Server" can refer to the hardware (computer storing web resources and software) or the software itself(that controls how users interact with hosted files, minimum functionality HTTP)

- #### Express : is a Node framework that simplifies HTTP verbs and allows for concise creation of HTTP verb handlers, simple integration with different view engines (i.e. porting information into front end templates), creates common settings such as port to use for connecting, and allows for additional request processing (middleware) to be inserted into request handling.

- #### Routing : Routing is how the client request is connected to the code they will receive

- #### WRRC : This is how information flows through a web app: client opens brower/enters url, request gets sent to the server which takes the url request, server follows it's routing to serve back the requested web document and passes it to the view, the view renders the information in the desired format back to the client in their browser.

 
---
# Preview

 

- ### Which 3 things had you heard about previously and now have better clarity on? about get post delete method
 

- ### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?  nothing
 

- ### What are you most excited about trying to implement or see how it works? nothing