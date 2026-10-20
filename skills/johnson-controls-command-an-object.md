---
name: command-an-object
description: Discover the commands an object supports and send one.
api: johnson-controls:metasys-rest-api
operations: [createToken, getObjectCommands, putObjectCommand]
generated: '2026-10-20'
method: generated
---
1. `createToken` for a bearer token.
2. `getObjectCommands` to list commands valid for the object.
3. `putObjectCommand` to issue one. No idempotency key exists and no undo is documented, so confirm before sending.
