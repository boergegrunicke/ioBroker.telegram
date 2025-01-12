![Logo](admin/telegram.png)
# ioBroker telegram Adapter

![Number of Installations](http://iobroker.live/badges/telegram-installed.svg)
![Number of Installations](http://iobroker.live/badges/telegram-stable.svg)
[![NPM version](http://img.shields.io/npm/v/iobroker.telegram.svg)](https://www.npmjs.com/package/iobroker.telegram)

![Test and Release](https://github.com/iobroker-community-adapters/iobroker.telegram/workflows/Test%20and%20Release/badge.svg)
[![Translation status](https://weblate.iobroker.net/widgets/adapters/-/telegram/svg-badge.svg)](https://weblate.iobroker.net/engage/adapters/?utm_source=widget)
[![Downloads](https://img.shields.io/npm/dm/iobroker.telegram.svg)](https://www.npmjs.com/package/iobroker.telegram)

Use Telegram service to communicate with ioBroker

## Documentation

[en Documentation](./docs/en/README.md)

<!-- [🇩🇪 Dokumentation](./docs/de/README.md) -->

## Sentry

**This adapter uses Sentry libraries to automatically report exceptions and code errors to the developers.** For more details and for information how to disable the error reporting see [Sentry-Plugin Documentation](https://github.com/ioBroker/plugin-sentry#plugin-sentry)! Sentry reporting is used starting with js-controller 3.0.

## Todo
- GUI tests for admin config
- GUI tests for rules

## Changelog
<!--
	Placeholder for the next version (at the beginning of the line):
	### **WORK IN PROGRESS**
-->
### 2.0.1 (2023-10-10)
* (boergegrunicke) Incorrect trailing zero in callback of sendTo() has been fixed. [#680]
* (mcm1957) Dependencies have been updated.

### 2.0.0 (2023-10-09)
* (bluefox) Packets were updated.
* (bluefox) BREAKING CHANGE: The minimal node.js version is 16
* (boergegrunicke) BREAKING CHANGE: Return an object with chatId and messageId instead of the message count

### 1.16.0 (2023-06-16)
* (foxriver76) We have added support for the `notification-manager` adapter

### 1.15.6 (2023-02-17)
* (bluefox) Implemented the optional escaping of characters in blockly
* (bluefox) Added the possibility to send updates of states only by changes
* (bluefox) Added option to select the quality of stored images

### 1.15.5 (2023-02-16)
* (bluefox) Added possibility to set `parse_mode` in the text message

## License

The MIT License (MIT)

Copyright (c) 2016-2023, bluefox <dogafox@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
