# nodejs-security3

Hash, Encrypt and Decrypt with Node.js Crypto module.

###### Salt 2

* [salt2.js](https://github.com/kkamara/nodejs-security3/blob/main/src/salt2.js).

```bash
  yarn node src/salt2.js
```

## Installation

* [Node.js](https://nodejs.org/en/)
* [yarn](https://yarnpkg.com/).

```bash
  cp .env.example .env
  yarn install
```

## Usage

```bash
  yarn node src/salt2.js
```

##### Run database migrations

```bash
  yarn node src/index.js
```

##### Run start
```bash
  yarn start # Runs Start-script `yarn node src/app.js`
  # Serves app to http://localhost:3000/.
  # Serves api to http://localhost:3000/api/v1.
  #   Example api route: http://localhost:3000/api/v1/test.
```

###### Reload server on project files change

```bash
  yarn dev # Runs Dev-script `nodemon src/app.js`
  # We can also `APP_ENV=development nodemon src/app.js`.
```


## Using docker?

* [docker](https://docs.docker.com/engine/install/) 
* [docker-compose](https://docs.docker.com/compose/install/).

```bash
  docker-compose up --build -d
```

## To run api tests

```bash
  yarn test
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[BSD](https://opensource.org/licenses/BSD-3-Clause)
