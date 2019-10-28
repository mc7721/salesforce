# SalesForce API Definitions
This is a working repository for SalesForce API definitions, providing machine readable artifacts that can be used to work with their REST API--helping streamling your integration with the very powerful API.

- [Documentation](https://documenter.getpostman.com/view/35240/SVzua1S6?version=latest)
- [Postman Collection](https://www.getpostman.com/collections/baaafb7925fba6aa999b)
- [Postman Environment](https://github.com/api-evangelist/salesforce/blob/master/postman-enviornment.json)
- [OpenAPI](https://github.com/api-evangelist/salesforce/blob/master/openapi.yaml)

You are welcome to fork and use this Postman collection or OpenAPI definition. Before you do, there are a couple things you need to consider:

- Authentication - You will need to setup your own application within your SalesForce account, and obtain your own secrets and keys and add them to the Postman environment before using.
- Design - SalesForce has an API for pulling all the objects from their system and leans on developers to add those to each call as part of a path parameter. I have incorporated each of these into path for each API call, and organized them by object area. 
- Completeness - I focused on making sure all objects were available for v20.0 of the API. In the future we might consider publishing a folder for each version and separate set of definitions for each version.
- Source of Truth - The Postman collection is the source of truth here, and the OpenAPI is generated from that. We will be maintaining and evolving the Postman collection, then generation API and publishing both here.

This README for these SalesForce API definitions will remain the central place to engage with and evolve this set of definitions. If there are specific paths you'd like to see added to this collection, or find things missing, please submit a GitHub issue for this repository to let us know, or feel free to submit a pull request against any of the definitions or this README.

<center>[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.getpostman.com/run-collection/baaafb7925fba6aa999b)</center>


