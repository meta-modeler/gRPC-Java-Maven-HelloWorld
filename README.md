# gRPC-Java-Maven-HelloWorld

The project has been created to illustrate how to use gRPC in the form of a simple HelloWorld application. The interface definition proto file, the source codes of both the server and the client are almost the same as the ones deployed here:
https://github.com/grpc/grpc-java
However, the project structure is different as the project:
- is maven multimodular one
- is split into three elements: server, client and interface
- the building responsibilities are distributed correctly among the POM files
- all maven plugins and other projects versions are defined in one place
- does not contain tests
- contains namespaces, which are changed according to the Wrocław University of Science and Technology inverted domain name convention convention
The project builds correctly under Windows (verified) and perhaps under other operating sysetms (not checked yet).

My other Maven projects may be helpful when starting the investigation of the content of this project:
- the one for building the executable Jar files:
https://github.com/meta-modeler/maven-executable-jar
- the one for creating multimodule Maven projects:
https://github.com/meta-modeler/maven-multimodule-project
