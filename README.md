react-widgets
=============

[![NPM version][npm-image]][npm-url]
[![Downloads][downloads-image]][downloads-url]
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FdanMateer%2Freact-widgets.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FdanMateer%2Freact-widgets?ref=badge_shield)

An à la carte set of polished, extensible, and accessible form inputs built for React.

__Demos and Documentation [here](http://jquense.github.io/react-widgets/)__

### Install

`npm install react-widgets`


### Local development and contributing

React widgets, uses a "monorepo" organization style for managing multiple npm packages
in a single git repo. This is done through a [Yarn](https://yarnpkg.com/en/) feature called
workspaces. To get everything setup and dependencies installed:

- make sure you have the __latest__ version of yarn installed
- run `yarn run bootstrap` in the repo root directory

#### Running the doc site locally

 - Follow the steps above
 - switch to the `www` directory and run `yarn`
 - `yarn run develop` to start the site

#### Running the storybook examples
  - follow the general install instructions
  - run `yarn start-dev`

### Old Browser Support

The goal is to support IE9+, but it is difficult for me to test a wide variety of browsers so there is no guarantee it will work (patches welcome!).

[npm-image]: https://img.shields.io/npm/v/react-widgets.svg?style=flat-square
[npm-url]: https://npmjs.org/package/react-widgets
[downloads-image]: http://img.shields.io/npm/dm/react-widgets.svg?style=flat-square
[downloads-url]: https://npmjs.org/package/react-widgets


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FdanMateer%2Freact-widgets.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FdanMateer%2Freact-widgets?ref=badge_large)