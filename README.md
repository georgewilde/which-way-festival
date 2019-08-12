# Which Way Festival

## Build

### Prerequisites

- Node & NPM

### Run locally

- `npm i` - install dependencies
- `npm start` - start development server

#### Where are generated files?

In `development` mode `webpack` does not write generated files to disk, in order to change it 
switch `devServer.writeToDisk` to `true` in [webpack.dev.js](./webpack.dev.js)

#### Run production build

- `npm run preview` 

### Production

- `npm run build` to prepare `html`, `css`, `js` files in `dist/` directory
