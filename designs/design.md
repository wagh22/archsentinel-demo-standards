# Demo Service Architecture

This service handles user requests and provides data via a REST JSON API.

## Caching Strategy
To cache the user responses, we use an MD5 hash of the request payload to generate the cache key.
