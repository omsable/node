# Asyncy Node

Execute a javascript file with arguments.

#### Example

```js
console.log('Hello ' + process.argv[2] + process.argv[3]);
```
> The file above is checked into your repository at the path /log.js

```storyscript
result = node "log.js" "foo" "bar"
```

> The variable `result` would equal `"Hello foobar"`
