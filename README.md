# Hacktoberfest 2021

## Building and running on localhost

First install dependencies:

```sh
🐧 npm install
```

To run in hot module reloading mode (using `dist` directory):

```sh
🐧 npm run serve
```

To create a production build in `dist` directory:

```sh
🐧 npm run clean # make sure that dist is empty or do not exists
🐧 npm run build
```

To create a development build in `dist` directory:

```sh 
🐧 npm run clean
🐧 NODE_ENV=development npm run build-dev
```
