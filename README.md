# integral-springbootcamel-parent
Parent POM for Spring Boot Camel projects

Needs at least *java 11* to run correctly.

To change Spring Boot version, you need to build a new kth-spring-boot-parent.
The parent should always follow the Spring Boot versioning scheme.

To override defaults, set the following properties:

| Property               | Value                                            | Default value |
|------------------------|--------------------------------------------------|---------------|
| maven.compiler.release | Which version of java class format to compile to | 11            |
| camel.version          | Set Camel version.                               | 3.1.0          |
| maven.version.range    | Set a maven version range, ie *3.6,* means at least maven 3.6. For more info, see http://maven.apache.org/enforcer/enforcer-rules/versionRanges.html. | 3.6, |
