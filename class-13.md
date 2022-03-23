> # Local Storage

### HTML5 storage (aka Web Storage, Local Storage, or DOM Storage)

- provided directly within most browsers (unlike previous attempts at local storage)
- accessed via the object `localStorage` in the global object `window`

- `setItem()` method will overwrite an existing value in a key-value pair
- `getItem()` method, when applied to a non-existent key, returns `null` rather than creating an error

- instead of `getItem()` and  `setItem()` you can get (see line 1 below) and set (see line 2 below) values using bracket notation:

```js
let item = localStorage['key';
localStorage['key'] = new;
```

- you can look up the total number of values in `localStorage` and iterate through it via indexes
