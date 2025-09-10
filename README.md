# SPARQL View Materialization Containers Specification
The shape index specification repository.
An online version is available at [this hypermedia link](https://ecrum19.github.io/sparql-view-materialization-containers/).
The specification is written in "pure" HTML, Javascript, and CSS, so it does not require building. The `./index.html` contains all the documentation.
Issues about the website or proposition of improvement can be made via the [github issues](https://github.com/ecrum19/sparql-view-materialization-containers/issues).

## Abstract

This specification defines a lightweight, file-system–backed cache for SPARQL queries and results, exposed as a Linked Data Platform (LDP) Container. 
It standardizes resource layout, metadata, and HTTP interactions so that clients and tools can discover cached SPARQL queries, their canonical algebra, provenance, and serialized results in a consistent way.
...

## Publish

You find an example configs in the folder `configs`:
- Use `github.json` if your repo is on GitHub.
- Use `gitlab.json` if your repo is on Gitlab.

These configs tell the Spec Platform to create a new build of the spec for every commit.
The platform will install the Node.js dependencies and run the build script.
The first time the platform only creates a build for the latest commit.
You find more information about configs 
[here](https://gitlab.ilabt.imec.be/KNoWS/spec-platform/orchestrator#spec-config).
Add your updated config file with a meaningful name to 
[this folder](https://gitlab.ilabt.imec.be/KNoWS/spec-platform/pipeline/-/tree/main/configs?ref_type=heads)
via a merge request.

## Copyright and license

ReSpec uses a default copyright and license.
Please make sure that it fits your requirements.
