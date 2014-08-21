[![License](http://img.shields.io/badge/license-MIT-brightgreen.png)](http://github.com/amd/furious.js/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/amd/furious.js.svg?branch=master)](https://travis-ci.org/amd/furious.js)

[![Dependency Status](https://david-dm.org/amd/furious.js.png)](https://david-dm.org/amd/furious.js)
[![OptionalDependency Status](https://david-dm.org/amd/furious.js/optional-status.png)](https://david-dm.org/amd/furious.js#info=optionalDependencies)
[![devDependency Status](https://david-dm.org/amd/furious.js/dev-status.png)](https://david-dm.org/amd/furious.js#info=devDependencies)

[![Browser Support](https://ci.testling.com/amd/furious.js.png)](https://ci.testling.com/amd/furious.js)

# Furious.js

Furious.js is a scientific computing package for JavaScript. Furious.js features:

- Provides n-dimensional array (NDArray) class
- Programming interface similar to NumPy
- Works with all modern browsers and Node.js
- Accelerates computation on Portable Native Client (PNaCl) and WebCL
- Computes asynchronously, without stalling the GUI
- Functionality covered with unit tests ([Try it!](https://amd.github.io/furious.js/unittest.html))
- Comes with extensive documentation

## Backends

Currently Furious.js provides three computational backends:

- JavaScript backend that works in all modern JS engines (Typed Array support required).
- Portable Native Client that works in Google Chrome and other Chromium-based browsers.
- WebCL backend that can be used with Node.js (via [node-webcl](https://www.npmjs.org/package/node-webcl)) and [WebKit-WebCL](https://github.com/SRA-SiliconValley/webkit-webcl).

Normally Furious.js would automatically detect the optimal backend, but it is possible to specify it manually.
