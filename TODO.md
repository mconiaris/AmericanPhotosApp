#American Photos TODO

## Current Install
* Research scripts in package.json
* Research purpose of angular-cli.json. A tutorial suggests that I add bootstrap there but npm install bootstrap did not.
* Do I manually put Bootstrap in angular-cli.json?


## Second MacBook Pro
$ npm update
npm WARN deprecated nodemailer@2.7.2: All versions below 4.0.1 of Nodemailer are deprecated. See https://nodemailer.com/status/
npm WARN deprecated node-uuid@1.4.8: Use uuid module instead
npm WARN deprecated socks@1.1.10: If using 2.x branch, please upgrade to at least 2.1.6 to avoid a serious bug with socket data flow and an import issue introduced in 2.1.0
npm WARN deprecated socks@1.1.9: If using 2.x branch, please upgrade to at least 2.1.6 to avoid a serious bug with socket data flow and an import issue introduced in 2.1.0
npm WARN deprecated mailcomposer@4.0.1: This project is unmaintained
npm WARN deprecated buildmail@4.0.1: This project is unmaintained
npm WARN prefer global node-gyp@3.6.2 should be installed with -g

> fsevents@1.1.3 install /Users/mconiaris/dev/AmericanPhotosApp/node_modules/fsevents
> node install

[fsevents] Success: "/Users/mconiaris/dev/AmericanPhotosApp/node_modules/fsevents/lib/binding/Release/node-v59-darwin-x64/fse.node" is installed via remote

> uws@9.14.0 install /Users/mconiaris/dev/AmericanPhotosApp/node_modules/uws
> node-gyp rebuild > build_log.txt 2>&1 || exit 0


> node-sass@4.8.3 install /Users/mconiaris/dev/AmericanPhotosApp/node_modules/node-sass
> node scripts/install.js

Downloading binary from https://github.com/sass/node-sass/releases/download/v4.8.3/darwin-x64-59_binding.node
Download complete ░⸩ ⠋ :
Binary saved to /Users/mconiaris/dev/AmericanPhotosApp/node_modules/node-sass/vendor/darwin-x64-59/binding.node
Caching binary to /Users/mconiaris/.npm/node-sass/4.8.3/darwin-x64-59_binding.node

> uglifyjs-webpack-plugin@0.4.6 postinstall /Users/mconiaris/dev/AmericanPhotosApp/node_modules/@angular/cli/node_modules/webpack/node_modules/uglifyjs-webpack-plugin
> node lib/post_install.js


> node-sass@4.8.3 postinstall /Users/mconiaris/dev/AmericanPhotosApp/node_modules/node-sass
> node scripts/build.js

Binary found at /Users/mconiaris/dev/AmericanPhotosApp/node_modules/node-sass/vendor/darwin-x64-59/binding.node
Testing binary
Binary is fine
american-photos-app@0.0.1 /Users/mconiaris/dev/AmericanPhotosApp
├── @angular-devkit/core@0.3.2 
├── @angular-devkit/schematics@0.3.2 
├── @angular/animations@5.2.9 
├── @angular/cli@1.7.3 
├── @angular/common@5.2.9 
├── @angular/compiler@5.2.9 
├── @angular/compiler-cli@5.2.9 
├── @angular/core@5.2.9 
├── @angular/forms@5.2.9 
├── @angular/http@5.2.9 
├── @angular/language-service@5.2.9 
├── @angular/platform-browser@5.2.9 
├── @angular/platform-browser-dynamic@5.2.9 
├── @angular/router@5.2.9 
├── @types/jasmine@2.8.6 
├── @types/jasminewd2@2.0.3 
├── @types/node@9.4.7 
├── ajv@6.4.0 
├── bootstrap@4.0.0 
├── codelyzer@4.2.1 
├── core-js@2.5.4 
├── jasmine-core@3.1.0 
├── jasmine-spec-reporter@4.2.1 
├── jquery@3.3.1 
├── karma@2.0.0 
├── karma-chrome-launcher@2.2.0 
├── karma-coverage-istanbul-reporter@1.4.2 
├── karma-jasmine@1.1.1 
├── karma-jasmine-html-reporter@0.2.2 
├── popper.js@1.14.1 
├── protractor@5.3.0 
├── rxjs@5.5.8 
├── ssri@5.3.0 
├── ts-node@5.0.1 
├── tslint@5.9.1 
├── typescript@2.6.2 
├── UNMET PEER DEPENDENCY webpack@2.7.0
├── webpack-dev-server@3.1.1 
└── zone.js@0.8.20 

npm WARN webpack-dev-server@3.1.1 requires a peer of webpack@^4.0.0-beta.1 but none was installed.
npm WARN webpack-dev-middleware@3.0.1 requires a peer of webpack@^4.0.0 but none was installed.
npm WARN extract-text-webpack-plugin@3.0.2 requires a peer of webpack@^3.1.0 but none was installed.


## Install Follup Ups
npm WARN extract-text-webpack-plugin@3.0.2 requires a peer of webpack@^3.1.0 but none is installed. You must install peer dependencies yourself.
npm WARN file-loader@1.1.6 requires a peer of webpack@^2.0.0 || ^3.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN html-webpack-plugin@2.30.1 requires a peer of webpack@1 || ^2 || ^2.1.0-beta || ^2.2.0-rc || ^3 but none is installed. You must install peer dependencies yourself.
npm WARN istanbul-instrumenter-loader@3.0.0 requires a peer of webpack@^2.0.0 || ^3.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN less-loader@4.0.5 requires a peer of webpack@^2.0.0 || ^3.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN uglifyjs-webpack-plugin@1.1.8 requires a peer of webpack@^2.0.0 || ^3.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN webpack-dev-middleware@1.12.2 requires a peer of webpack@^1.0.0 || ^2.0.0 || ^3.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN webpack-dev-server@2.11.1 requires a peer of webpack@^2.2.0 || ^3.0.0 but none is installed. You must install peer dependencies yourself.
npm WARN webpack-subresource-integrity@1.0.4 requires a peer of webpack@^1.12.11 || ~2 || ~3 but none is installed. You must install peer dependencies yourself.




##Reference Pages
* How to Install npm: https://docs.npmjs.com/getting-started/installing-node
* Building a Web app from scratch: https://code.tutsplus.com/tutorials/building-a-web-app-from-scratch-in-angularjs--net-32944
* Angularjs docs: https://docs.angularjs.org/tutorial/step_00
* How to migrate away from Bower? https://bower.io/blog/2017/how-to-migrate-away-from-bower/
* Yarn and Webpack: https://snyk.io/blog/bower-is-dead/
* Yeoman: http://yeoman.io/codelab/scaffold-app.html#toc
* nvm (node version manager) documentation: https://github.com/creationix/nvm/blob/master/README.md#installation

