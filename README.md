# colorful-terminal-logger

[![npm version](https://img.shields.io/npm/v/colorful-terminal-logger.svg?style=flat-square)](https://www.npmjs.com/package/colorful-terminal-logger)
[![npm downloads](https://img.shields.io/npm/dt/colorful-terminal-logger.svg?style=flat-square)](https://www.npmjs.com/package/colorful-terminal-logger)
[![license](https://img.shields.io/npm/l/colorful-terminal-logger.svg?style=flat-square)](https://github.com/yourusername/colorful-terminal-logger/blob/master/LICENSE)

A colorful terminal logger built with Node.js using Winston, Chalk, and Moment.js.

## Installation

You can install the `colorful-terminal-logger` package via npm:

```bash
npm install colorful-terminal-logger
```

## Usage

```javascript
const logger = require('colorful-terminal-logger');

logger.info('Information message');
logger.warn('Warning message');
logger.error('Error message');
```

## Options

You can customize the logger's behavior by passing options to the `createLogger` function. Refer to the [Winston documentation](https://github.com/winstonjs/winston) for more information on available options.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
