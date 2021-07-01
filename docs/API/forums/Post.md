# Post

The post object. Represents a forum post.
You can get this object by using the [ScratchSession.`getPost(id)`](./../ScratchSession/#scratchsessiongetpost(id)) function.

## Functions

### `update(body)`
Updates the post with the given bbcode (the `body` parameter).

| Parameter  | type    | Description                                       |
| :--------- | :-----: | ------------------:                               |
|  body      | string  | The bbcode you want to update the signature with. |

## Properties

### `content.html`
The HTML of the post.

### `content.bb`
The BBCode of the post.

### `id`
The id of the post.

### `topic`
The post's topic id.

### `author`
The author of the post.

### `postedAt`
A UTC string of the time the post was posted.