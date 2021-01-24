# nibeuplink-openapi

This repo contains an openapi 3-compliant documentation of the Nibe Uplink API. It can be used to generate strongly-typed clients using tools like NSwag or https://editor.swagger.io/

It mirrors the official documentation (https://api.nibeuplink.com/docs/v1) with the following exceptions:

- Object System was renamed to NibeSystem to resolve name conflicts
- Due to inconsistency on Nibe's side, certain enums have a "NONE" value added as the first element if they are not zero-based in the documentation
