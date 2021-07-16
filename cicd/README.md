# Overview

The intent of the contents in this `cicd` folder is multi purposed. It has the configuration
used for testing [Ploigos](https://github.com/ploigos), it also has the base configuration used
if using this application as a sample app when deploying the
[ploigos-software-factory-operator](https://github.com/ploigos/ploigos-software-factory-operator).
Any of this content can also be used as references for creating your own CI/CD configuration.

# Intended Uses

## Ploigos Development

The contents under [cicd/ploigos-integration-environment](./ploigos-integration-enviornment)
are hard coded to the environment used to do integration testing of [Ploigos](https://github.com/ploigos).
Its primary purpose is to be used for integration testing. Its secondary purpose is as a reference
that others can copy to use for their applications in their environments.

Note that each type of reference workflow for each type of workflow runner tool is in
[cicd/ploigos-integration-environment](./ploigos-integration-enviornment) for the purpose of
all the different integration test scenarios. If using this as a reference in your environment
you should delete all the content you don't need including redundant workflows or DSL files
for workflow runner tools not being used. It is also recommended the contents are placed directly
under the `cicd/` folder, or whatever folder structure makes sense to you, but there is no
need to keep the multiple nesting of folders needed for our integration testing purposes.

## Operator Starter Project
TODO
