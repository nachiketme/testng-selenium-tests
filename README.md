# TestNG Selenium tests

Simple Selenium tests designed to be run against a Selenium grid using TestNG.
Has two tests which hit https://www.google.co.uk/ and perform a search.

The browser used is configured in /src/main/resources/application.properties, update to change browser or selenium hub url.

To run tests:

```
mvn test
```
