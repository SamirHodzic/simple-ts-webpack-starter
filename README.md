# Simple Typescript Webpack Starter

[![Dependencies][dependencies]][dependencies-url]
[![Dev Dependencies][dev-dependencies]][dev-dependencies-url]

>Simple Typescript starter kit using webpack for packaging. Perfect for bootstraping your Typescript project / module regardless any framework.

## Built on

- [Webpack](https://github.com/webpack/webpack)
- [Typescript](https://github.com/Microsoft/TypeScript)
- [Webpack Dashboard](https://github.com/FormidableLabs/webpack-dashboard)

# Getting started

## Clone Simple Typescript Webpack Starter

```bash
git clone https://github.com/SamirHodzic/simple-ts-webpack-starter.git
cd simple-ts-webpack-starter
# Install the dependencies
npm install
```

## Run

Start a Webpack dev server 
```bash
npm start
```
Your app should be live on URL: `http://localhost:3000`

Start a Webpack server with the production configuration 
```bash
npm run server:prod
```


## Build Only
Build a development release
```bash
npm run build
```


Build a production release
```bash
npm run build:prod
```
After build phase, 3 files are generated into the `dist` folder:
- `app.bundle.js` - contains the core of the application. From the entry point `src/index.ts`
- `vendor.bundle.js` - contains the vendor dependencies
- `index.html` - html page with references to the 2 files above

[dependencies]: https://david-dm.org/samirhodzic/simple-ts-webpack-starter.svg
[dependencies-url]: https://david-dm.org/samirhodzic/simple-ts-webpack-starter
[dev-dependencies]: https://david-dm.org/samirhodzic/simple-ts-webpack-starter/dev-status.svg
[dev-dependencies-url]: https://david-dm.org/samirhodzic/simple-ts-webpack-starter?type=dev