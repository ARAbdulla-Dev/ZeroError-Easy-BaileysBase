<br />
<h1 align="center">ZeroError-Easy-BaileysBase</h1>

No more ERRORS when using [whiskeySockets/Baileys](https://github.com/@whiskeySockets/Baileys) anymore... Use Baileys Easily to make up your bot!

## Features

- Error handling correctly.
- No unnecessary stops when running.
- Connection is provided.
- Easy to debug errors.
- Live time activity monitoring

## Screenshot

<img src="https://i.ibb.co/mDqkwk2/Screenshot-2024-06-09-173900.png" width="100%"/>


## Installation

First clone the respirotary by downloading directly it from github or

using the git
> git clone github.com/ARAbdulla-Dev/ZeroError-Easy-BaileysBase

Then install the required dependencies using [npm.](https://npmjs.org)

> npm i  @whiskeysockets/baileys@6.7.4 chalk@2.4.2 node-fetch@2.7.0 path@0.12.7 pino@9.1.0 puppeteer@22.10.0 qrcode-terminal@0.12.0

Then edit the main.js file as needed and run the main file.

> node main.js


## Usage

Use it as the official [whiskeySockets/Baileys](https://github.com/@whiskeySockets/Baileys).

```javascript
const connectToWhatsApp = require('./base');

async function startWhatsApp() {
    const { sock } = await connectToWhatsApp();
    
    // Sock is the main object contaning all the functions including connection...
    // I would provide you the connection...
    // You can do anything here...

    /*
    Ex:-

    sock.sendMessage(remoteJid, {text: "Hi"});

    */
    
}

startWhatsApp();
```

- For any help contact me on [WhatsApp.](https://wa.me/94704281955?text=Hi)
- Also don't forget to star ✨ this Repo if it is helpful.

<br>
<hr>