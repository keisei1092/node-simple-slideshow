node-simple-slideshow
================

simple slideshow webapp with [Express](http://expressjs.com).

Usage
-----

```sh
$ git clone https://github.com/keisei1092/node-simple-slideshow
$ cd node-simple-slideshow
$ mkdir public/images
```

* Place some image files to `./public/images/` you want to use in slideshow. Then,

```sh
$ npm install
$ DEBUG=myapp:* npm start
```

If you can't run the server, I missed some package in `package.json`... Please install by hand.

License
-------

MIT