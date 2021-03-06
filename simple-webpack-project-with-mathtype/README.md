# Simple Froala Webpack Project Example
This covers the basic directions to get up and running with webpack. 

<img src='./example.gif'>

## Configure
If you're creating your webpack configuration from scratch, these plugins will be needed. 

### Webpack

* Run `npm install --save-dev webpack`
* Run `npm install --save-dev webpack webpack-cli`
* Run `npm install --save-dev path`
* Run `npm install webpack-dev-server --save-dev` 

### Webpack Plugins
The html-webpack-plugin will copy the `index.html` template to the dist folder and add the bundle.js resource to it. 

* Run `npm install --save-dev html-webpack-plugin`
* Run `npm install --save-dev clean-webpack-plugin`
* Run `npm install --save-dev style-loader`
* Run `npm install --save-dev css-loader`

### Froala Editor

* Run `npm install froala-editor`

### MathType for Froala
Find out more [here](https://www.npmjs.com/package/@wiris/mathtype-froala3).

* Run `npm install @wiris/mathtype-froala3`
* Run `npm install jquery`

## Download Dependencies
If you copy or delete the `./node_modules` folder, download the dependencies first.

* Run `npm install`

## Debug
This will run webpack and it observes the changes and will output the changes to the `./dist` directory.

* Run `npm start`
* Open the webpack generated file [http://localhost:9000](http://localhost:9000) in a browser.
