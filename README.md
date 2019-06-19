# Vessel route component

This component shows how to display the latest position of a vessel, identified by its `imo`, and its route to a target location `(latitude, longitude)`. Both the vessel position and the route to a target location are fetched from [searoutes' APIs](https://developer.searoutes.com/). Specifically:

- the route: https://api.searoutes.com/v2/route
- the vessel position: https://api.searoutes.com/vs/vessel-positions

To request a trial key, send an email to <contact@searoutes.com>.

## Prerequisites

In addition to an API key from searoutes (see above), you need a token from [mapbox](https://account.mapbox.com/) to run this component.

## Install

Install yarn
```sh
$ npm install --global yarn
```
Install application dependencies
```sh
$ yarn install
```

In `./demo/` create a `config.js` file, use `template.config.js` as a model.

## Run

From the root directory of this repository run:
```
$ yarn start
```
