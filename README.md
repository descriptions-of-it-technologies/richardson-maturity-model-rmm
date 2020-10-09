# Richardson Maturity Model (RMM).





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Richardson Maturity Model.](#richardson-maturity-model)
* [Richardson Maturity Model (RMM) Levels.](#richardson-maturity-model-rmm-levels)
* [Level 0: Swamp of POX.](#level-0-swamp-of-pox)
* [Level 1: Resources.](#level-1-resources)
* [Level 2: HTTP Verbs.](#level-2-http-verbs)
* [Level 3: Hypermedia.](#level-3-hypermedia)
* [Summary.](#summary)
* [Help](#help)





## About.





## Documentation.
* [Richardson Maturity Model.](https://www.google.com/search?q=richardson+maturity+model&oq=Richardson+ma&aqs=chrome.1.69i57j0l4j46l3.7412j0j7&sourceid=chrome&ie=UTF-8)






## Richardson Maturity Model.
* Established by Leonard Richardson in a 2008 Q-Con Presentation.
* A model used to describe the maturity of RESTful services.
* Unlike SOAP, there is no formal specification for REST.
* RMM is used to describe the quality of the RESTful service.





## Richardson Maturity Model (RMM) Levels:
* Level 3: Hypermedia Controls
* Level 2: HTTP Verbs
* Level 1: Resources
* Level 0: The Swap of POX





## Level 0: Swamp of POX.
* POX - Plain Old XML.
* Uses implementing protocol as a transport protocol.
* Typically uses one URI and one kind of method.
* Examples - RPC, SOAP, XML-RPC.





## Level 1: Resources.
* Uses Multiple URIs to identify specific resources.
* Examples:
  * http://www.example.com/product/1234
  * http://www.example.com/product/5687
* Still uses a single method (ie GET).





## Level 2: HTTP Verbs.
* HTTP Verbs are used with URIs for desired actions.
* Examples:
  * GET /products/1234 - to return data for product 1234.
  * PUT /products/1234 (with XML body) to update data for product 1234.
  * DELETE /products/1234 to delete product 1234.
* Most common in practical use.





## Level 3: Hypermedia.
* Representation now contains URIs which may be useful to consumers.
* Helps client developers explore the resource.
* No clear standard at this time.
* Spring provides an implementation of HATEOS.





## Summary.
* Level 1 - breaks large service into distinct URIs
* Level 2 - Introduces Verbs to implement actions
* Level 3 - provides discoverability, making the API more self documenting





## Help.
