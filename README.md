
# Koop Sample App
[![Build Status](https://travis-ci.org/koopjs/koop-sample-app.svg?branch=master)](https://travis-ci.org/koopjs/koop-sample-app)
[![Greenkeeper badge](https://badges.greenkeeper.io/koopjs/koop-sample-app.svg)](https://greenkeeper.io/)

A sample [Koop](https://github.com/koopjs/koop) application with some common [providers](https://koopjs.github.io/docs/providers).

This app makes it easy to get started running your own instance of Koop. It's also helpful for trying out Koop's functionality and testing providers, caches, plugins, and deployments.

If you're new to [Node.js](https://nodejs.org/) development, you can read more about [setting up a development environment](https://koopjs.github.io/docs/setup).

## Instructions

Clone this repository on your machine.

```
git clone git@github.com:koopjs/koop-sample-app.git
```

Change the working directory to the newly created `koop-sample-app` folder.

```
cd koop-sample-app
```

Install dependencies.

```
npm install
```

Start the server.

```
npm start
```

Take Koop for a test drive!

This sample app includes the following providers:

* [`agol`](https://github.com/koopjs/koop-provider-agol)
* [`zillow`](https://github.com/dmfenton/koop-provider-zillow)
* [`craigslist`](https://github.com/dmfenton/koop-provider-craigslist)

Optional:

To configure the provider below:

* [`trimet`](https://github.com/koopjs/koop-provider-trimet)

1. sign up for a [developer key](https://developer.trimet.org/appid/registration/)
2. reference it in `/koop-provider-trimet/config/default.json`
3. copy/paste the file into `/koop-sample-app/config/`

## Deploying

### Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/koopjs/koop-sample-app)

### Now
1. Install [Now](https://zeit.co/now)
2. run `now -e PORT=80`

## Resources

* [Koop](https://github.com/koopjs/koop)
* [Koop Documentation](https://koopjs.github.io/docs)
* [PostgreSQL](http://www.postgresql.org/)
* [PostGIS](http://postgis.net/)
* [ArcGIS for Developers](http://developers.arcgis.com)
* [ArcGIS REST API Documentation](http://resources.arcgis.com/en/help/arcgis-rest-api/)
* [@esri](http://twitter.com/esri)

## License

[Apache 2.0](LICENSE)
