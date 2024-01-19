# cs - The Ultra Shorthand Console

`cs` provides a minimalistic wrapper around the standard `console` object in JavaScript, enabling you to use shorthand notation to output logs, errors, and more. Perfect for developers who want to save keystrokes and time without reinventing the wheel.

## Features 😎
- Ultra shorthand syntax: `cs.log` instead of `console.log`
- Supports all common `console` methods: `log`, `error`, `warn`, `info`, `debug`, etc.
- Easy to install and use in both Node.js and Bun environments

## Installation 🚀

### Using Node.js

To install `cs` with npm, run the following command in your project directory:

```sh
npm install cs-shorthand
```

Or with Yarn:

```sh
yarn add @cs-shorthand
```

### Using Bun

To install `cs` with Bun, run:

```sh
bun add cs-shorthand
```

## Usage 🛠

Firstly, require `cs` in your JavaScript file:

```javascript
// For Bun or ES Modules
import cs from 'cs-shorthand';
```

Now you can use `cs` just like you would use `console`:

```javascript
cs.log('Hello, world!'); // Regular log
cs.error('Oops, something went wrong.'); // Error log
cs.warn('This is a warning.'); // Warning log
cs.info('FYI: Here is some info.'); // Info log
cs.debug('Debugging time.'); // Debug log
```

## Contributing 👋

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/your-username/cs/issues). Make sure to follow the [contribution guidelines](CONTRIBUTING.md) when you submit pull requests.

## License 📄

Distributed under the MIT License. See `LICENSE` for more information.

---

Happy coding! ✨ 

