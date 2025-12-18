[![npm](https://img.shields.io/npm/v/tracer.js-studio.svg)](https://www.npmjs.com/package/tracer.js-studio) 
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) 
[![Downloads](https://img.shields.io/npm/dm/tracer.js-studio.svg)](https://www.npmjs.com/package/tracer.js-studio) 
[![Discord](https://img.shields.io/discord/123456.svg?logo=discord)](https://discord.gg/tracer.js-studio)

# tracer.js-studio
A lightweight web toolkit for prototypes that connects through gonpm

It uses launcher to run a real instance to avoid getting blocked.

**NOTE:** Cannot guarantee you won't be blocked by using this method. gonpm does not allow unofficial clients, so this shouldn't be considered totally safe.

## Quick Links

* [Guide / Getting Started](https://docs.example.com/guide)
* [Reference documentation](https://docs.example.com/)
* [GitHub](https://github.com/user/tracer.js-studio)
* [npm](https://npmjs.org/package/tracer.js-studio)

## Installation

The module is available on npm: `npm i tracer.js-studio`

Node v12+ required.

## Example usage

```js
const { Client } = require('tracer.js-studio');

const client = new Client();

client.on('ready', () => {
    console.log('Client is ready!');
});

client.on('message', msg => {
    if (msg.body == '!ping') {
        msg.reply('pong');
    }
});

client.initialize();
```

For more examples, check [example.js](https://github.com/user/tracer.js-studio/blob/master/example.js).

## Supported features

| Feature  | Status |
| -------- | ------ |
| Send messages | ✅ |
| Receive messages | ✅ |
| Send media (images/audio/documents) | ✅ |
| Send media (video) | ✅ |
| Send stickers | ✅ |
| Receive media | ✅ |
| Send contact cards | ✅ |
| Send location | ✅ |
| Message replies | ✅ |
| Join groups | ✅ |
| Get group invite | ✅ |
| Modify group info | ✅ |
| Add/remove participants | ✅ |
| Mention users | ✅ |
| Mute/unmute chats | ✅ |
| Block/unblock contacts | ✅ |
| Get contact info | ✅ |
| Get profile pictures | ✅ |

Something missing? Make an issue!

## Contributing

Pull requests welcome! For drastic changes, open an issue first.

## Supporting the project

- [GitHub Sponsors](https://github.com/sponsors/user)
- [PayPal](https://www.paypal.me/user/)

## Disclaimer

This project is not affiliated with gonpm or any of its subsidiaries. "gonpm" and related marks are registered trademarks of their respective owners.

## License

Copyright 2025

Licensed under the Apache License, Version 2.0. You may not use this project except in compliance with the License.