# ionize-wallet-proton

## Development Setup (All Platforms)

### Dependencies

#### You will need the following dependencies installed before you can proceed to the "Setup" step:

- Node.JS (Latest LTS version - 10.x) https://nodejs.org/

- Yarn https://yarnpkg.com/en/

- Git https://git-scm.com/downloads

Tip: If you already have a different version of node.js installed besides 10.x, try using [Node Version Manager](https://github.com/nvm-sh/nvm#install--update-script).

#### Setup

First, clone the repo via git:

```bash
git clone https://github.com/Ionize-Project/ionize-wallet-proton
```

And then install the dependencies with yarn.

```bash
$ cd ionize-wallet-proton
$ yarn
```

Next copy the `Config.js` file to the `turtlecoin-wallet-backend` folder inside `node_modules`.

```
$ cp turtlecoin-wallet-backend/dist/lib/Config.js node_modules/turtlecoin-wallet-backend/dist/lib/Config.js
```

Run the wallet.

```bash
$ yarn start
```

### Starting Development

Start the app in the `dev` environment. This starts the renderer process in [**hot-module-replacement**](https://webpack.js.org/guides/hmr-react/) mode and starts a webpack dev server that sends hot updates to the renderer process:

```bash
$ yarn dev
```