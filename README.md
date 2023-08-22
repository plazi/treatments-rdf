# Treatments-RDF

This repository contains rdf data in the turtle format.

This data is generated from plazi/treatments-xml using Xalan/XSLT (XML → RDF-XML) and Rapper (RDF-XML → Turtle). For more information, see the [plazi/treatments-xml](https://github.com/plazi/treatments-xml) repository, which contains the Github Action responsible.

From here the data is picked up by [PSPS](https://github.com/factsmission/psps/) and made available through a public [SPARQL](https://www.w3.org/TR/sparql11-query/) endpoint at https://treatments.ld.plazi.org (note: access is read-only and HTTP requests must be using the GET method).
