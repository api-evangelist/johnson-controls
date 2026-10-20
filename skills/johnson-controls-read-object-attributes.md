---
name: read-object-attributes
description: Authenticate to a Metasys site director and read objects and their attribute values.
api: johnson-controls:metasys-rest-api
operations: [createToken, getObjects, getObject, getObjectAttribute]
generated: '2026-10-20'
method: generated
---
1. `createToken` with username/password to get a JWT; send it as `Authorization: Bearer <token>` (default expiry 30 minutes).
2. `getObjects` to list objects; pick an object id.
3. `getObject` / `getObjectAttribute` to read values. Base URL is `https://{hostname}/api/v6` on the customer's own server.
