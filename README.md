# PWA-TextEditor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A text editor that can create notes or code snippets with or without an internet connection.

![mock-up](./Assets/J-A-T-E.png)

## Table of Contents
- [Technology](#technology)
- [Installation](#installation)
- [Usage](#usage)
- [Heroku](#heroku)
- [Questions](#questions)

## Technology
* Express.js
* IndexedDB
* babel-loader
* css-loader
* style-loader
* Webpack
* html-webpack-plugin
* webpack-pwa-manifest
* code-mirror-themes

## Installation
Install npm package that client/server need by using the following command:
```bash
npm install
```

Then,
```
  npm run build
  npm run start:dev
```


## Usage

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```


## Heroku
[Deployed Link](https://fast-atoll-62823.herokuapp.com/)


## Questions
if you have more question, reach me out below.
* Github repository : https://github.com/rogseo
* email : rogseo@gmail.com