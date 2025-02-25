---
Title: RedisJSON commands 
linkTitle: Commands 
description: Lists RedisJSON commands and provides links to the command reference pages.
weight: 25
alwaysopen: false
toc: "false"
categories: ["Modules"]
---

The following table lists RedisJSON commands. See the command links for more information about each command's syntax, arguments, and examples.

| Command | Description |
|---------|-------------|
| [JSON.ARRAPPEND](https://redis.io/commands/json.arrappend/) | Appends an element to a JSON array. |
| [JSON.ARRINDEX](https://redis.io/commands/json.arrindex/) | Returns the index of a value's first occurrence in a JSON array. |
| [JSON.ARRINSERT](https://redis.io/commands/json.arrinsert/) | Inserts JSON values into a JSON array before the given index. |
| [JSON.ARRLEN](https://redis.io/commands/json.arrlen/) | Returns the length of a JSON array. |
| [JSON.ARRPOP](https://redis.io/commands/json.arrpop/) | Removes and returns an element located at the index in the JSON array. |
| [JSON.ARRTRIM](https://redis.io/commands/json.arrtrim/) | Trims a JSON array so that it contains only the specified inclusive range of elements. |
| [JSON.CLEAR](https://redis.io/commands/json.clear/) | Clears container values (arrays/objects) and sets numeric values to 0. |
| [JSON.DEBUG](https://redis.io/commands/json.debug/) | Debugging container command. |
| [JSON.DEBUG HELP](https://redis.io/commands/json.debug-help/) | Returns helpful information about the [JSON.DEBUG](https://redis.io/commands/json.debug/) command. |
| [JSON.DEBUG MEMORY](https://redis.io/commands/json.debug-memory/) | Reports a JSON element's memory usage in bytes. |
| [JSON.DEL](https://redis.io/commands/json.del/) | Removes a JSON element. |
| [JSON.FORGET](https://redis.io/commands/json.forget/) | Removes a JSON element, the same as [JSON.DEL](https://redis.io/commands/json.del/). |
| [JSON.GET](https://redis.io/commands/json.get/) | Returns the value of an element in JSON-serialized form. |
| [JSON.MGET](https://redis.io/commands/json.mget/) | Returns the values of multiple elements. |
| [JSON.NUMINCRBY](https://redis.io/commands/json.numincrby/) | Increments the number stored at path by the specified number. |
| [JSON.NUMMULTBY](https://redis.io/commands/json.nummultby/) | Multiplies the number stored at path by the specified number. (deprecated as of RedisJSON v2.0) |
| [JSON.OBJKEYS](https://redis.io/commands/json.objkeys/) | Returns the keys contained in the specified JSON object. |
| [JSON.OBJLEN](https://redis.io/commands/json.objlen/) | Returns the number of keys in the specified JSON object. |
| [JSON.RESP](https://redis.io/commands/json.resp/) | Returns a JSON element in [Redis Serialization Protocol (RESP)](https://redis.io/docs/reference/protocol-spec/) format. |
| [JSON.SET](https://redis.io/commands/json.set/) | Sets the value of a JSON element. |
| [JSON.STRAPPEND](https://redis.io/commands/json.strappend/) | Appends the given string to the specified key's existing strings. |
| [JSON.STRLEN](https://redis.io/commands/json.strlen/) | Returns the length of a string. |
| [JSON.TOGGLE](https://redis.io/commands/json.toggle/) | If the boolean is `true`, changes it to `false`. If the boolean is `false`, changes it to `true`. |
| [JSON.TYPE](https://redis.io/commands/json.type/) | Returns a JSON element's type. |
