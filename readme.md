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

// simple usage, with 25 second expiration
cache('my-unique-key', { "hello": "world" }, 5000)

// simple usage, with no expiration
cache('my-unique-key2', { "hello": "world" })
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

