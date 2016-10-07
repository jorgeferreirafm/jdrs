# Java Document Rendering Service (JDRS)


JDRS is an application that aims to provide an easy and robust way of managing and create documents based on the different templates formats.


Main goals:

- Be able to render diferent formats of documents
- Be able to create dinamic documents based on templates and the list of values sent
- Be managed using a web application, allowing the definition of templates
- Expose a set of webservices to handle remote document rendering requests
- Agnostic of the formats
- Be able of refreshing the information after a document being render


Additional goals:

- Option of merging two or more documents of the same format
- Converter different formats



Design 

- core-api : Define the interfaces and extension points
- web-admin : provides a web page to manage templates and repoositories




