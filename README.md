# Quickstart for Node.js in the App Engine standard environment

This is the sample application for the
[Quickstart for Node.js in the App Engine standard environment][tutorial]
tutorial found in the [Google App Engine Node.js standard environment][appengine]
documentation.

* [Universal Rendering](#universal-rendering)
* [Setup](#setup)
* [Running locally](#running-locally)
* [Deploying to App Engine](#deploying-to-app-engine)
* [Running the tests](#running-the-tests)

## Universal Rendering 

To host in any remote server than can run node.js, like Google Cloud Platform

Follow steps in [Universal Rendering Wiki](https://github.com/angular/angular-cli/wiki/stories-universal-rendering)

Create a new repo with contents of dist folder and configuring to run server.js file. 

Repo for deploying this project in Google Cloud Platform is [Google Host](https://github.com/MonikaRavi/MyRecipeBook-googlehost)

Visit my [Google Cloud Platform Site](https://recipebook-ingredients.appspot.com/signin)

## Setup

Before you can run or deploy the sample, you need to do the following:

1.  Refer to the [appengine/README.md][readme] file for instructions on
    running and deploying.
1.  Install dependencies:

    With `npm`:

        npm install


## Running locally

With `npm`:

    npm start



## Deploying to App Engine

With `npm`:

    npm run deploy


## Running the tests

See [Contributing][contributing].

[appengine]: https://cloud.google.com/appengine/docs/standard/nodejs
[tutorial]: https://cloud.google.com/appengine/docs/standard/nodejs/quickstart
[readme]: ../../README.md
[contributing]: https://github.com/GoogleCloudPlatform/nodejs-docs-samples/blob/master/CONTRIBUTING.md
