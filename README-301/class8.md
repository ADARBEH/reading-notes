## What does REST stand for?

### REST is an acronym for REpresentational State Transfer and an architectural style for distributed hypermedia systems. 
--- 
## REST APIs are designed around a **resources**.

---
## What is an identifier of a resource? Give an example.

### A Uniform Resource Identifier (URI) is a character sequence that identifies a logical (abstract) or physical resource -- usually, but not always, connected to the internet. A URI distinguishes one resource from another.

```
{
https://adventure-works.com/orders/1

}
```
---
## What are the most common HTTP verbs?

- ##### The POST verb is most-often utilized to **create** new resources. In particular, it's used to create subordinate resources. That is, subordinate to some other (e.g. parent) resource. In other words

- ##### The HTTP GET method is used to **read** (or retrieve) a representation of a resource. In the “happy” (or non-error) path, GET returns a representation in XML or JSON 

- ##### PUT is most-often utilized for **update** capabilities, PUT-ing to a known resource URI with the request body containing the newly-updated representation of the original resource.

- ##### PATCH is used for **modify** capabilities. The PATCH request only needs to contain the changes to the resource, not the complete resource.

## What should the URIs be based on?
### URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

---
## Give an example of a good URI.

```
{
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid
}
```



### What status code does a successful GET request return?
`status code 200 (OK).`
### What status code does an unsuccessful GET request return?
` 404 (Not Found)`
### What status code does a successful POST request return?
`status code 201 (Created)`
### What status code does a successful DELETE request return?
`status code 204 (No Content)`
