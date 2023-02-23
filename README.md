
# Preact Template

## CLI Commands

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# test the production build locally
npm run serve

# run tests with jest and enzyme
npm run test
```

For detailed explanation on how things work, checkout the [CLI Readme](https://github.com/developit/preact-cli/blob/master/README.md).

# Code Structure
```
├── README.md
├── package-lock.json
├── package.json
├── src
│   ├── assets
│   │   ├── favicon.ico
│   │   └── icons
│   │       ├── android-chrome-192x192.png
│   │       ├── android-chrome-512x512.png
│   │       ├── apple-touch-icon.png
│   │       ├── favicon-16x16.png
│   │       ├── favicon-32x32.png
│   │       └── mstile-150x150.png
│   ├── components
│   │   ├── app.js
│   │   └── header
│   │       ├── index.js
│   │       └── style.css
│   ├── index.js
│   ├── manifest.json
│   ├── routes
│   │   ├── home
│   │   │   ├── index.js
│   │   │   └── style.css
│   │   └── profile
│   │       ├── index.js
│   │       └── style.css
│   ├── style
│   │   └── index.css
│   ├── sw.js
│   ├── template.html
│   └── util
│       ├── api_fetch.js
│       └── storage_handler.js
├── tests
│   ├── __mocks__
│   │   ├── browserMocks.js
│   │   ├── fileMocks.js
│   │   └── setupTests.js
│   └── header.test.js
```
## Definition of folders under src
- assets - where icons, images, fonts and the like should be placed
- components - contains reusable elements that can be imported by a page or other components
- routes - where main entry point of every page should be placed.
- style - for global classes of css.
- util - where helper functions or class should be placed
- tests - where unit tests scripts should be placed

