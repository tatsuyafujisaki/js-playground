# How to create `.eslintrc.js`
```shell
npm init -y # creates package.json
npm install eslint --save-dev # installs a style guide along the way if package.json exists.
npx eslint --init
```

# Note
## How to sort an array descendingly
```js
xs.sort(function(a, b){return a-b});
```

## How to convert an array to a set
```js
new Set(xs);
```

## How to get the second largest element of an array, ignoring duplicate elements
```js
[...new Set(xs)].sort((a, b) => b - a)[1];
```

# References
https://eslint.org/docs/user-guide/configuring
