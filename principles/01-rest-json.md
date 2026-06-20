---
id: REST-JSON-001
title: "All APIs must be RESTful and use JSON"
severity: high
description: "APIs must use JSON and avoid legacy XML or SOAP."
criteria:
  forbids_terms:
    - xml
    - soap
tags:
  - architecture
  - api
  - standards
---

# All APIs must be RESTful and use JSON

We strictly use JSON over HTTP for APIs.
