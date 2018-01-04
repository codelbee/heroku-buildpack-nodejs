# Heroku Buildpack for Node.js

This is a fork of the [official Node buildpack](https://github.com/heroku/heroku-buildpack-nodejs) that just
installs Node, but doesn't run `yarn` or `npm`.

All the changes are deletions from `bin/compile`.

The tests for this version don't pass.