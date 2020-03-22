# AngularHeroTeam
This project is attached to article related to How to change Angular Karma/Jasmine test framework by Jest and how to perform unit test using Jest

> https://blog.ineat-conseil.fr/2019/04/angular-remplacer-karma-jasmine-par-jest

## 01-Init-switch-Karma-Jasmine-to-Jest branch
Initial project generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.5. And replace Karma/Jasmine test framework by Jest

Checkout branch, `run npm install` or `yarn install`
Run `ng serve` to show the Angular Hello World App throught your favorite brwser at `http://localhost:4200/`
Run `ng test`to execute default Angular Hello World App unit test using Jest

## 02-Hero-App-Untested
Small Angular Application to create Team of Hero and Team of Wicked using clean architecture but not tested

## 03-Hero-App-FullyTested
Same previous application but fully tested with Jest

## 04-Hero-App-Service
Same app with untested api service called. The api was mocked using json-server and running using concurrently.
Use `npm run start` or `yarn start` to start concurrently json-server and Web Server (ng serve).

## 05-Hero-App-Service-Tested
Same app with tested service.

# Lien utile :
CheatSheet (https://github.com/sapegin/jest-cheat-sheet/blob/master/Readme.md) qui regroupe différentes méthodes disponibles au niveau de l’API pour effectuer vos tests avec Jest.
(https://jestjs.io/docs/en/getting-started) jest docs
(https://itnext.io/how-i-do-configure-jest-to-test-my-angular-8-project-2bd84a21d725) Config 
(https://github.com/ahasall/angular-jest-demo) setting
(https://stackoverflow.com/questions/58498885/angular-8-and-jest-file-not-found-jest-preset-angular-inlinehtmlstripstylestr) Angular 8 and jest - File not found: jest-preset-angular/InlineHtmlStripStylesTransformer.js

# git fetch all
```
git branch -r | grep -v '\->' | while read remote; do git branch --track "${remote#origin/}" "$remote"; done
git fetch --all
git pull --all
```
