# fastify-cloudevents-validator

  [![Code Style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](http://standardjs.com/)
  [![dependencies Status](https://david-dm.org/smartiniOnGitHub/fastify-cloudevents-validator/status.svg)](https://david-dm.org/smartiniOnGitHub/fastify-cloudevents-validator)
  [![devDependencies Status](https://david-dm.org/smartiniOnGitHub/fastify-cloudevents-validator/dev-status.svg)](https://david-dm.org/smartiniOnGitHub/fastify-cloudevents-validator?type=dev)

Fastify web application that act as a validator for CloudEvents


## Setup and run

To complete project setup, do:
```
npm install
```

and run with
```
npm start
```

then point your browser to [localhost:8000](http://localhost:8000)


## Setup and run with Docker

Note that it's possible to let Docker do all inside a container, because all is described in a Dockerfile; 
see [Dockerfile-usage](./Dockerfile-usage.md) for related commands.
Of course you need a local installation of Docker (recent, if possible latest), but nothing other.


## Usage

TODO: ...


## Others

To run a development server (with hot reload enabled) instead execute this:
```
npm run start:dev
```

For other custom commands look the 'scripts' section inside 'package.json'.


## Requirements

Fastify 2.1.0 or later, Node.js 10.x or later.


## Note

All CloudEvents features exposed here are in the the library [cloudevent](https://npmjs.org/package/cloudevent/), 
wrapped here in the Fastify plugin [fastify-cloudevents](https://www.npmjs.com/package/fastify-cloudevents).


## References

For more info on the CloudEvents standard, see the [CloudEvents Specification](https://github.com/cloudevents/spec).


## License

Licensed under [Apache-2.0](./LICENSE).

----
