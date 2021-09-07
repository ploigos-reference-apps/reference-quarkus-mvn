# reference-quarkus-mvn
A reference application that is built and unit tested with Maven
that can be run through the [Ploigos](https://github.com/ploigos) workflows.

Configured to run the following workflows:

* Jenkins
  * minimal
  * typical
  * everything
* Tekton
  * minimal
  * typical
  * everything

Tested with:
* Ploigos v0.21.0

## Source
This is a copy/paste/fork of [rest-json-quickstart](https://github.com/quarkusio/quarkus-quickstarts/tree/master/rest-json-quickstart)
maintained specifically do integration testing for [Ploigos](https://github.com/ploigos).

It has also been updated to use the latest Quarkus and Java 11.
