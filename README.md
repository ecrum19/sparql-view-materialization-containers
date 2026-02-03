# SPARQL View Materialization Containers Specification
The SPARQL View Materialization Containers Specification repository.
An online version is available at [this hypermedia link](https://ecrum19.github.io/sparql-view-materialization-containers/).
The specification is written in "pure" HTML, Javascript, and CSS, so it does not require building. The `./index.html` contains all the documentation.
Issues about the website or proposition of improvement can be made via the [github issues](https://github.com/ecrum19/sparql-view-materialization-containers/issues).

## Abstract

The execution of SPARQL queries can be challenging for a number of reasons including performance, availability, and reproducibility. To encourage greater reproducibility, sharability, and performance of these queries, a result caching approach offers a pragmatic solution. This specification defines SPARQL Query View Materialization Containers (QVMC): HTTP resources that implement the Linked Data Platform (LDP) Container model to store SPARQL query definitions and their corresponding materialized result sets. A QVMC is an ldp:BasicContainer whose members include SPARQL query source files and SPARQL Results documents. An RDF index resource describes the contained views and how they were generated. These guidelines enable clients and tools to reliably leverage cached SPARQL queries, their canonical algebra, provenance, and serialized results, in a way that promotes interoperability and reuse.


## Copyright and license

Copyright © 2025 the document editors/authors. Text is available under the Creative Commons Attribution 4.0 International Public License.

