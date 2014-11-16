## A Simple Ember.js Example App w/ Twitter Bootstrap

* Bootstrap via Bower package `bootstrap-sass-official`
* Sass via `broccoli-sass`
* Some minor configuration and file generation...

### Some Notes

- Override Bootstrap variables as needed in `app/styles/bootstrap_variables.scss`
- Bootstrap (SCSS) imported via `app/styles/bootstrap_imports.scss`
- Take note of the minor modifications to `Brocfile.js`

### Quick Start

```shell
git clone git@github.com:erikthedeveloper/emberjs-bootstrap3-starter-app.git MyEmberApp
cd MyEmberApp
git checkout -b feature/my_first_feature
npm install
bower install
ember server
```

Now you should be able to browse to: [http://localhost:4200](http://localhost:4200) and be up and running with Ember.js and Bootstrap 3!

It should look a bit like this:

![](https://cloud.githubusercontent.com/assets/1240178/5063715/e19a5b76-6dae-11e4-86cc-d32bc233908d.png)

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM) and [Bower](http://bower.io/)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at http://localhost:4200.

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

* ember: http://emberjs.com/
* ember-cli: http://www.ember-cli.com/
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

