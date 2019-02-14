# spring-config-baeldung-tutorial

Example to answer this question:

[https://stackoverflow.com/questions/48794257/spring-cloud-config-not-getting-properties/]

For server execution, use delivery-config-server:

```console
gradle clean build && java -jar build\libs\delivery-config-server-0.0.1-SNAPSHOT.jar
```

For client execution, use delivery-config-client:

```console
gradle clean build && java -jar build\libs\delivery-config-client-0.0.1-SNAPSHOT.jar
```
