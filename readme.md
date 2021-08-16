![Cover](https://raw.githubusercontent.com/fwd/cache/master/.github/cover.png)

<h1 align="center">@fwd/cache 💾</h1>

> A NodeJS package to simplify in-memory caching.

## Install

```sh
npm install fwd/cache
```

## Usage

```js

const cache = require('@fwd/cache')


// store something in-memory
cache('my_unique_key', 'my value')


// get that something
var my_unique_key = cache('my_unique_key') 

console.log(my_unique_key) // my value


// you may also pass an expiration delay as a third parameter
cache('my_unique_key', 'my value', 10000) // 10 seconds in ms


// wait 10 seconds
setTimeout(() => {
	cache('my_unique_key') // undefined
}, 10000) // 10 seconds in ms

```

## 👤 Author

**Forward Miami**

* Github: [@fwd](https://github.com/fwd)
* Website: [https://forward.miami](https://forward.miami)

## 🤝 Contributing

Contributions, issues and feature requests are welcome! Feel free to check [issues page](https://github.com/fwd/cache/issues).

## ⭐️ Show your support

Give a star if this project helped you, and help us continue maintaining this project by contributing to it or becoming a sponsor.

[Become a sponsor to fwd](https://github.com/sponsors/fwd)

## 📝 License

Copyright © 2020 [Forward Miami](https://forward.miami). This project is [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html) licensed.
