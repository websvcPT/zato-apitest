
Then header "{header}" is "{value}"
=============================================================================================================

Usage example
-------------

```
Feature: zato-apitest docs

Scenario: Then header "{header}" is "{value}"

    Given address "http://apitest-demo.zato.io"
    Given URL path "/demo/json"

    When the URL is invoked

    Then header "Connection" is "keep-alive"
```

Discussion
----------

(None)