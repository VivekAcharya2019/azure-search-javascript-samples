# JavaScript / JQuery based Samples for Accessing an Azure Search Service
This repository contains samples that show how to interact with Azure Search from a JavaScript client.  

## Important Note

It is important to note, that a JavaScript application that accesses Azure Search directly has the disadvantage from a security standpoint that the API Key needs to be stored on the client side.  For that reason, you should certainly only leverage Query API Keys where possible and typically only leverage direct connection (meaning not via a Web App) in cases where the users can be trusted.

## Real Estate Search Demo

This sample shows a number of capabilities including:
* Full Text Search
* Multi-Select Faceting and Filtering
* Autocomplete
* Paging

[Live Demo](https://liamca.github.io/RealEstateDemoJS/index.html)

[Code](https://github.com/liamca/azure-search-javascript-samples/tree/master/RealEstateDemoJS)

![Real Estate Search Demo for Azure Search in JavaScript](https://github.com/liamca/azure-search-javascript-samples/raw/master/RealEstateDemoJS/RealEstateDemoScreenShot.png)
