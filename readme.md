<h1 align="center">@fwd/cache 💿</h1>

> A Node.js library that simplifies cache storage.

## Install

```sh
npm install @fwd/cache
# or
yarn add @fwd/cache
```

## Usage

### JSON File

```js

const cache = require('@fwd/cache')

// STORE STUFF

// simple usage, with no expiration
cache('my-key', { "hello": "world" }) 

// simple usage, with 5 second expiration
cache('mykey-2', { "hello": "world" }, 5000)

// RETRIVE STUFF

var myUniqueKey = cache('my-key')
// { "hello": "world" }

setTimeout(() => {
	var myUniqueKey2 = cache('mykey-2')
	// null
}, 5000)

```

## Author

👤  **Forward Miami**

* Github: [@fwd](https://github.com/fwd)
* Website: [https://forward.miami](https://forward.miami)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/fwd/cache/issues).

## Show your support

Help us continue maintianing and making cool stuff.

[Become a sponsor to fwd](https://github.com/sponsors/fwd)

Give a ⭐️ if this project helped you!

## 📝 License

### MIT

Copyright © 2020 [Forward Miami](https://forward.miami).

