# AmericanPhotosApp General Helpful Notes

## Node.js Tutorials:
* https://codehandbook.org/creating-a-web-app-using-angular-4/
* https://blog.risingstack.com/node-hero-tutorial-getting-started-with-node-js/

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Check for Updates
Run npm outdated, which will list packages that need to be updated.

run npm update in the same directory as the package.json file of the application that you want to update.

## Further help
To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


# Setup Notes
* Checked for npm installation and upgraded to latest version
* This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.8.
* February 14, 2018: ran ng new <app> to use a generator to install the app.
* March 5, 2018: Decided to go with npm as my front end package manager
* March 5, 2018: installed Boostrap


# General Principals
## Angular
* The app has an index.html page with the app-root component. By default the application has only the app-root component which is defined inside the src/app folder. Keep the AppComponent as the parent component and load components inside the AppComponent.