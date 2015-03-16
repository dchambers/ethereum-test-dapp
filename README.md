# ethereum-test-dapp

This is a very simple repository that makes it easy to run the Ethereum Test DApp.

To build the app run:

```bash
npm install
npm run build
```

You'll need a web server to serve the HTML files. I recommend
[simple-http-server](https://www.npmjs.com/package/simplehttpserver), which you can install as follows:

```bash
npm install simplehttpserver -g
```
and which you can then use to serve the files within the current directory like this:

```bash
simplehttpserver
```

For this to work you'll also need a version of Ethereum running on the `localhost` (I used
[ethereum-cpp PoC 8](https://github.com/ethereum/cpp-ethereum/tree/poc-8-tag)), which I ran as follows:

```bash
ethereum -rpc -mine
```
