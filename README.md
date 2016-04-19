# [OData](http://www.odata.org/) goes [OpenAPI](https://openapis.org/)

OpenAPI descriptions for live example OData services at [www.odata.org](http://www.odata.org/)

 - [Simple read/write service](http://petstore.swagger.io/?url=https://raw.githubusercontent.com/ralfhandl/odata/master/example.openapi.json)
 - [TripPin (read/write)](http://petstore.swagger.io/?url=https://raw.githubusercontent.com/ralfhandl/odata/master/TripPin.openapi.json)
 - [Northwind (read)](http://petstore.swagger.io/?url=https://raw.githubusercontent.com/ralfhandl/odata/master/Northwind.openapi.json)

OpenAPI descriptions for OData services that reference each other (cross-service references)
 - [People](http://petstore.swagger.io/?url=https://raw.githubusercontent.com/ralfhandl/odata/master/People.openapi.json)
 - [Products](http://petstore.swagger.io/?url=https://raw.githubusercontent.com/ralfhandl/odata/master/Products.openapi.json)

The OpenAPI descriptions have been created from the XML `$metadata` documents of these services with the [V4-CSDL-to-OpenAPI.xsl](https://tools.oasis-open.org/version-control/browse/wsvn/odata/trunk/spec/examples/V4-CSDL-to-OpenAPI.xsl) XSL transformation. 

ER diagrams generated with [yUML](http://yuml.me/).
