# SiteWatcher Template

SiteWatcher Template helps you to create browser extension to monitor changing of target website. The extension automatically check website recursively, and notify user when it is needed.

> Powered by [browser-extension-react-typescript-starter](https://github.com/sinanbekar/browser-extension-react-typescript-starter)

## Features

- **Recursive Exploration**: SiteWatcher automatically access the target website recursively, and judge wether site contents include target feature or not.
- **User Notifications**: When target feature appears, SiteWatcher notify user with browser notification and Line app.

#### Built with

- React
- TypeScript
- Redux (toolkit and redux-persist)
- TailwindCSS
- Vite
- Jest
- ESLint
- Prettier
- simple-git-hooks (lightweight husky alternative)
- nano-staged

[^1]: While it is fully supported and stable in most cases, hard reloading is rarely recommended.

## Browser Support

| [![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png)](/) | [![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png)](/) | [![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png)](/) | [![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)](/) | [![Brave](https://raw.github.com/alrra/browser-logos/master/src/brave/brave_48x48.png)](/) |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| ✔                                                                                             | ✔ (Beta)                                                                                         | ✔                                                                                       | ✔                                                                                          | ✔                                                                                          |

## Requirements

- [Node.js](https://nodejs.org) 16 or later installed
- [Yarn](https://yarnpkg.com) installed


## Quick Start

- `yarn install` to install dependencies.
- `yarn dev` to start the development server.
- `yarn build` to build an unpacked extension.

- **Load extension in Chrome (Chromium, Manifest V3)**

  - Go to the browser address bar and type `chrome://extensions`
  - Check the `Developer Mode` button to enable it.
  - Click on the `Load Unpacked Extension` button.
  - Select your `dist` folder in the project root.

- **Load extension in Firefox (Manifest V2)**

  - Go to the browser address bar and type `about://debugger`
  - Click on the `Load Temporary Add-on` button.
  - Select your `dist-firefox-v2` folder in the project root.

### Available Commands

- `yarn clean` to remove dist folder. `dev` and `build` commands call this command.
- `yarn format` to fix code with eslint and prettier.
- `yarn lint` to call ESLint and Prettier.
- `yarn test` for testing.

## Development


## License

MIT © [Shimei Yago](https://github.com/ShimeiYago)
