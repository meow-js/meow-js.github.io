# ScratchSession
All functions are async unless noted.

## Create a ScratchSession

```javascript
const { ScratchSession } = require('meowing')

let session = new ScratchSession(process.env.user, process.env.pass) // Logs in to scratch

session.login().then(async () => {
  // Logout
  await session.logout()  
})
```

## Functions
### `login()`
Logs the object into scratch.

### `getPost(id)`
Gets a [Forum Post](../forums/Post).

| Parameter  | type    | Description         |
| :--------- | :-----: | ------------------: |
|  id        | number  | The post id.        |

### `getTopic(id)`
Gets a [Topic](../forums/Topic).

| Parameter  | type    | Description         |
| :--------- | :-----: | ------------------: |
|  id        | number  | The topic id.       |

### `getForum(id)`
Gets a [Forum](../forums/Forum).

| Parameter  | type    | Description         |
| :--------- | :-----: | ------------------: |
|  id        | number  | The forum id.       |

### `getSignature()`
Gets the currently logged in user's [Signature](../forums/Signature).