<h1 align="center">Simple-console-colors 💻🌈🖥️</h1>
<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.1.1-blue.svg?cacheSeconds=2592000" />
  <a href=" ">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" target="_blank" />
  </a>
  <a href="https://github.com/MoralesJonathan/simple-console-colors/graphs/commit-activity">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" target="_blank" />
  </a>
  <a href="https://github.com/MoralesJonathan/simple-console-colors/blob/master/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" target="_blank" />
  </a>
</p>

> K.I.S.S - Simple Console Colors is a stupid simple coloring package for you terminal in node. Gives color to `console.info`, `console.warn`, and `console.error`; without having to use new methods or a different logger other than `console`. Just require the package and use console as normal. Thats it.

## 🖼️ Screenshots
<img alt="Screenshot" src="https://raw.githubusercontent.com/MoralesJonathan/imagehosting/master/simple-console-colors-screenshot1.png"/>

<img alt="Screenshot"  src="https://raw.githubusercontent.com/MoralesJonathan/imagehosting/master/simple-console-colors-screenshot2.png"/>


## 🛠️ Install
This is a Node.js module available through the npm registry.
<br/>Installation is done using the npm install command:

```sh
$ npm i simple-console-colors 
```

## 📑 Usage

Require the npm module and call it as a function. It takes an optional `string` parameter where you may chose different styles.
```sh
require('simple-console-colors')(style);
```

The supported styles are:
- boxy <br/> <img alt="Screenshot" width="300px" src="https://raw.githubusercontent.com/MoralesJonathan/imagehosting/master/simple-console-colors-screenshot3.png" />
- minimal <br/> <img alt="Screenshot" width="300px" src="https://raw.githubusercontent.com/MoralesJonathan/imagehosting/master/simple-console-colors-screenshot4.png" />
- basic <br/> <img alt="Screenshot" width="300px" src="https://raw.githubusercontent.com/MoralesJonathan/imagehosting/master/simple-console-colors-screenshot5.png" />
- default <br/> <img alt="Screenshot" width="300px" src="https://raw.githubusercontent.com/MoralesJonathan/imagehosting/master/simple-console-colors-screenshot2.png" />

If no style is passed, `default` is used.

## 🔬 Run tests

```sh
$ npm run test
```

## 👨🏻‍💻 Author

 **Jonathan Morales - <moralesjonathan@email.com>**

* Github: [@MoralesJonathan](https://github.com/MoralesJonathan)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [Issues page](https://github.com/MoralesJonathan/simple-console-colors/issues) and the [Contributing Guide](CONTRIBUTING.md).

## ❤️ Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2019 [Jonathan Morales <moralesjonathan@email.com>](https://github.com/MoralesJonathan).<br />
This project is [MIT](https://github.com/MoralesJonathan/simple-console-colors/blob/master/LICENSE) licensed.
