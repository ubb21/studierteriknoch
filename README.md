# studiert-sonstwer-noch

> This application provides a clock showing how long a given person is already studying.

## Build Setup

Build the node app:

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm start

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

Build the docker container:

``` bash
# build the docker container
make build

# run the docker container with certificates configured in deploy.env
make run

# to run the container with self-signed certificates for development use
make run-self-signed
```

## Fork this project for other students

1. Change the domain in `deploy/nginx.conf`
2. Configure variables in `src/config.js`
3. Change `favicon.png` and generate new favicons with `npm run icon`
4. Get your own [certificates](https://certbot.eff.org/)
5. Build the container and deploy it on your web-server