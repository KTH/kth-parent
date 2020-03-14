# kth-spring-boot-camel-parent
Parent POM for Spring Boot Camel projects

Needs at least *java 11* to run correctly.

Ignore warnings about *'version' contains an expression but should be a constant.*.

To change Spring Boot version, you need to build a new kth-spring-boot-parent.

To override defaults, set the following properties:

| Property               | Value                                            | Default value |
|------------------------|--------------------------------------------------|---------------|
| maven.compiler.release | Which version of java class format to compile to | 11            |
| camel.version          | Set Camel version.                               | 3.1.0          |
| maven.version.range    | Set a maven version range, ie *3.6,* means at least maven 3.6. For more info, see http://maven.apache.org/enforcer/enforcer-rules/versionRanges.html. | 3.6, |
