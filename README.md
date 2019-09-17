```bash
$ mvn io.quarkus:quarkus-maven-plugin:0.22.0:create \
    -DprojectGroupId=org.acme \
    -DprojectArtifactId=getting-started \
    -DclassName="org.acme.quickstart.GreetingResource" \
    -Dpath="/hello"
```


```bash
$  ./mvnw compile quarkus:dev:
```
