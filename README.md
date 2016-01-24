# Documentor

This is an Electron + Ember based document viewer app. Generally projects have generated documentation in form of html files and need some hosting. If your project is private then you can host the same on github pages. But if your github project is private then hosting is a big issue. Even for public projects the github pages website needs internet for access. 
Here I am planning to build a desktop tool which can download and sync your public and private github pages website locally.
Right now this project is in very early stage.

I am planning to build following features in this app
- Rendering locally downloaded static website using electron
- Integrating and cloning github branch locally
- Auth for github private repos
- Choosing local folders instead of github repos.
- github login.


## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

