# prdready20200826

## Setup
You must make sure that if you use my project you make use of your own Check-IN PAPI OAS spec from your OWN exchange.
You will have to change the `pom.xml` so that is uses your own dependency instead of mine.


Here's my dependency. **You only need to change the `groupId` to match your Organization ID found under Access Management**
```
    <dependency>
      <groupId>e43d24ea-28d9-4dbc-8027-8730cb941236</groupId>
      <artifactId>check-in-papi</artifactId>
      <version>1.0.0</version>
      <classifier>oas</classifier>
      <type>zip</type>
    </dependency>
```
Finally, you need to change the organization ID inside the `global.xml` for the APIkit global element.
