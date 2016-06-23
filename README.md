##JWT Debugger Extension

![JWT Debugger screenshot](/publishing/screenshot-2.png?raw=true)

### How to build
First, install the required dependencies:

```sh
npm install
```

In order to build the project execute:

```sh
grunt chrome-extension
```

The resulting files will be located in the ```dist``` directory. Open Chrome, go to ```Extensions```, enable ```Developer Mode```, and then load the unpacked extension from the ```dist``` directory.

### Hacking
Main JavaScript files are located inside the ```js``` directory.
HTML files are generated from the Jade files located in ```view```.
Dependencies are handled with ```npm``` and bundled using Webpack.
The ```extension-deps``` directory is for static dependencies.
