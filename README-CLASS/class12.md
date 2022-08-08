## In your own words, describe what each group of status code represents:

1. #### 100’s =they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. 

2. #### 200’s = These are the success codes. They tell the client that its request was accepted.

3. #### 300’s = They tell the client that the resource they are requesting isn’t available at the expected location anymore.

4. #### 400’s = These are the client error codes. They are all about invalid requests a client sent to a server. 

5. #### 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies.


## What is a status code 202?
#### response status code indicates that the request has been accepted for processing, but the processing has not been completed

## What is a status code 308?
#### redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers.

## What code would you use if an update didn’t return data to a client?
## `204 No Content`

## What code would you use if a resource used to exist but no longer does?
## `403 Forbidden`


## Why do we need to pull our MongoDB database string out of our server and put it into our .env?
#### To protect it because it is sensitive data

## What is middleware?
#### software that provides common services and capabilities to applications outside of what’s offered by the operating system. 

## What does app.use(express.json()) do?
#### is a built in middleware function in Express starting from v4.16.0. It parses incoming JSON requests and puts the parsed data in req.body

## What is the difference between PUT and PATCH?
- #### PUT is a method of modifying resource where the client sends data that updates the entire resource .   
- #### PATCH is a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data.

## What is the difference between a status 200 and a status 201?
- #### The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed.
- #### A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).