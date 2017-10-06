# raml

RAML stands for RESTful API Modeling Language. It's a way of describing practically-RESTful APIs in a way that's highly readable by both humans and computers.

Please Refer : https://raml.org/about-raml

This example for API Documentations using JSON, RAML, XSD Schemas.


Installation Steps:

1. Install Node. Path: https://nodejs.org/en/download/
2. Install ATOM. Path : https://atom.io/
3. Run below commands:
 3.1 apm config set strict-ssl null
 3.2 apm install api-workbench
 3.3 npm i -g raml2html
 3.4 npm install -g raml-cop	
 3.5 apm install -g raml-cop
 3.6 npm install -g ramltojaxrs	
 3.7 apm install -g ramltojaxrs
 
To generate HTML please run below command:

  raml2html COMPANIES.raml > COMPANIES.html
