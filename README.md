# ApiDeployTool
Java app that uses the Exchange, API Manager and Access Manager APIs to perform a complete configuration of an API.

Sample command line run from project's directory:
```
java -jar target/ApiDeployTool.jar registerApi myAnypointUser MyAnypointPassword "businessGroupName" myApi v1 "myEnvironmentName" base my-policies.json my-clients.json
```

The encrypt function requires the cps-encryption library, found here:

https://github.com/mulesoft-consulting/cps-encryption
