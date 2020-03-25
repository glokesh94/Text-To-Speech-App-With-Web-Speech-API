# Text-to-Speech Demo

**You can checkout the full article on Scotch: [How To Build A Text-To-Speech App With Web Speech API
](http://crowdforgeeks.com/tutorials/how-to-build-a-text-to-speech-app-with-web-speech-api).**

This project contains a demo source code showing how to build a simple text-to-speech voice app for the web using the Web Speech API.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. Before you begin, make sure you have [`npm`][npm] and [`node`][node] installed on your system.

Run the following commands to get started.

```sh
npm install
npm start
```

The app will run on port **`3000`** by default. If you would prefer another port, you can specify it in the `server.js` file. Look for the following line in the file and replace `3000` with your desired port.

```js
const PORT = process.env.PORT || 3000;
```


[node]: https://nodejs.org/en/
[npm]: https://npmjs.com/
