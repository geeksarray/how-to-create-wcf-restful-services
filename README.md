# How to Create WCF RESTful service

This article describes step by step creation of WCF RESTful services and its http methods like GET, PUT, DELETE and POST. In this article I am going to create a WCF rest service API which returns XML data as WCF attributes.

## What is RESTful WCF Service?
REST stands Representational state transfer works on http protocols. Any clients like ASP.net, C#, JAVA, jQuery who can communicate with http protocols can consume the WCF REST services. REST is stateless, sessionless and resource based architecture which helps you to easy access to wcf service and reduce message size.

## RESTful services uses common http verbs to perform operations.
GET: Retrieves the resource.
POST: Creates new resource or submits data to be processed.
PUT: Replace or update entire content of resource.
DELETE: Deletes existing resource.

## Files

1. **[IProduct WCF Service Contract](https://github.com/geeksarray/how-to-create-wcf-restful-services/blob/master/RESTFulWCFService/RESTFulWCFService/IProductService.cs)** - WCF Service contract created with interface.

1. **[ProductService WCF Service](https://github.com/geeksarray/how-to-create-wcf-restful-services/blob/master/RESTFulWCFService/RESTFulWCFService/ProductService.svc.cs)** - WCF Service contract implementation with RESTful architecture.


Following pictue shows the HTTP GET call to ProductService RESTful service and its response.

![WCF RESTful services](http://dotnetmentors.com/Images/WCFRestServiceResult.png)

For more details check - [How to create WCF RESTful service](https://geeksarray.com/blog/how-to-create-wcf-restful-services)
