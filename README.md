# Amplify

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Hosting angular app using amplify 

1. npm install -g @aws-amplify/cli
2. ng build
3. amplify init 
  set Distribution Directory Path to `dist/project-name`
  Set build command to `npm build run`
  Select authetiaction method based of your requirement. 
    Example Provide accesskeyId and secretAccessKey of user and select required region 
4. amplify configure project 
  Review above settings
5. npm run build
6. amplify add hosting 
  Select depending on your requirement I selected Hosting with Amplify Console Manual Deployment
7. amplify publish
8. Open the url you get at the end
  Example url : https://dev.d2akkgrflkhxoh.amplifyapp.com
