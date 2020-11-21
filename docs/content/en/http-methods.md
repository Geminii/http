---
title: HTTP Methods
description: 'HTTP Methods'
position: 9
category: API
---

<alert type="info">

See [here](/usage#making-requests) for usage information for below methods.

</alert>

<alert type="info">

Each http method returns a `Promise`

</alert>

### `delete`
### `get`
### `head`

- arguments: `(url, options?)`
- resolves: [Response](https://developer.mozilla.org/en-US/docs/Web/API/Response)
- rejects: `Error`

These methods corresponds to the similar named HTTP/1.1 methods.

### `patch`
### `post`
### `put`

- arguments: `(url, body?, options?)`
- resolves: [Response](https://developer.mozilla.org/en-US/docs/Web/API/Response)
- rejects: `Error`

These methods corresponds to the similar named HTTP/1.1 methods.

### `$delete`
### `$get`
### `$head`

- arguments: `(url, options?)`
- resolves: `JSON`
- rejects: `Error`

These `$`-prefixed convenience methods always return the requested content as [`JSON`](https://developer.mozilla.org/en-US/docs/Web/API/Body/json).

### `$patch`
### `$post`
### `$put`

- arguments: `(url, body?, options?)`
- resolves: `JSON`
- rejects: `Error`

These `$`-prefixed convenience methods always return the requested content as [`JSON`](https://developer.mozilla.org/en-US/docs/Web/API/Body/json).
