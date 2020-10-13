# RESTful API.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Richardson Maturity Model (RMM).](https://github.com/descriptions-of-it-technologies/richardson-maturity-model-rmm)
* [RESTful Web Services.](#restful-web-services)
* [RESTful Terminology.](#restful-terminology)
* [Pros.](#pros)
* [Cons.](#cons)
* [Best practices.](#best-practices)
* [Help](#help)





## About.





## Documentation.





## RESTful Web Services:
* Because of their simplicity and versatility, RESTful web services have become the de facto standard for web services.
* REST - Representational State Transfer.
  * Representation - Typically JSON or XML.
  * State Transfer - Typically via HTTP.
  * Established by Roy Fielding from his 2000 doctoral dissertation.





## RESTful Terminology.
* Verbs - HTTP Methods: GET, PUT, POST, DELETE
* Messages - the payload of the action (JSON/XML)
* URI - Uniform Resource Identifier
  * A unique string identifying a resource
* URL - Uniform Resource Locator
  * A URI with network information - http://www.example.com
* Idempotence:
  * Wikipedia “Idempotence is the property of certain operations in mathematics and computer science that they can be 
    applied multiple times without changing the result beyond the initial application.”
  * In other words, you can exercise the operation multiple times, without changing the result.
  * Example: Refreshing a web page (HTTP GET operation)
* Stateless - Service does not maintain any client state
* HATEOAS - Hypermedia As The Engine of application State
  * Wikipedia - “a REST client should then be able to use server-provided links dynamically to discover all the available 
    actions and resources it needs. As access proceeds, the server responds with text that includes hyperlinks to other 
    actions that are currently available.”





## Pros.





## Cons.





## Best practices.
* Consumer first.
* Make best  user of HTTP: Request Methods, Response Status.
* No secure info in URL.
* Use plurals in definition of paths.
* Use nouns for resources.





## Help.
