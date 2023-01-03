# Udacity Advanced front-end Nanodegree Project:

# Evaluate a news article with Natural Language Processing


# Technologies and Languages Used:

- Backend-Server:
  - ExpressJS(NodeJS)
  - Async/Await
- UI (Front-end):
  - Vanilla Javascript
  - Sass
  - HTML
- Tools:
  - Webpack
  - Github

## Run project

Below shows how to run in development and production mode.

### Download Dependencies

`npm install`

### run in development mode

To start the webpack dev server at port 8080

` $ npm run build-dev`

Start back-end server
`npm run start`

### run in production mode

Generate the dist files and then start server at port 3000

` $ npm run build-prod` 

` $ npm run start`
## Configs files

- Webpack
  - Dev Configs: `webpack.config.dev.js`
    - Not optimized build
    - source map
  - Production `webpack.config.prod.js`
    - Optimized build
    - Auto generated HTML from template
- Dependency
  - `package.json`

## Offline Functionality

The project have service workers set up in webpack to provide the offline functionality of our app. When the service worker is functioning correctly, you will see the below message when you inspect the browser.



