# multiple-cy-examples [![CircleCI](https://circleci.com/gh/bahmutov/multiple-cy-example/tree/master.svg?style=svg)](https://circleci.com/gh/bahmutov/multiple-cy-example/tree/master)

See [circle.yml](circle.yml) and [package.json](package.json)

There is one version of Cypress in folder [one](one) and another version in folder [two](two).

## Top level support and plugins

Both project files use common [support.js](support.js) and [plugins.js](plugis.js) files placed in the root of the monorepo. Each `cypress/support/index.js` just imports this top level `support.js` for example.

See [two/cypress/plugins/index.js](two/cypress/plugins/index.js) for example.
