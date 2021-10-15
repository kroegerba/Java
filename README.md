
# Java
#### Maven
If you are uncertain what you want, the preferred phase to call is
`mvn verify`
This command executes each default lifecycle phase in order (validate, compile, package, etc.), before executing verify. You only need to call the last build phase to be executed, in this case, verify. In most cases the effect is the same as package. However, in case there are integration-tests, these will be executed as well.
#### Running
The package phase (Maven) provides us a single .jar-file in the target-directory which contains all of its dependecies. We can execute it like this:
`java -jar Java-1.0-SNAPSHOT.jar`

