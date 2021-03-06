A [koa + socket.io + redis](http://koajs.com) generator for [Yeoman](http://yeoman.io).

    .
    ├── bin
    │   └── www.js
    │
    ├── middleware
    │
    ├── controllers
    │   └── index.js
    │
    ├── resource
    │   ├── js
    │   │	│── page
    │   │	│── cmp
    │   │	│── tools
    │   │	└── lib
    │   └── css
    │       └── index.css
    ├── test
    │   └── routeSpec.js
    ├── views
    │   ├── public
    │   │		│──head.html
    │   │
    │   ├── template.html
    │   └── index.html
    │
    ├── app.js
    ├── begin.sh
    └── package.json

## Install

Install with [npm](https://npmjs.org).

```
$ npm install -g yo
```

```
$ npm install -g generator-koa-socketio
```

Make a new directory and ```cd``` into it:

```
$ mkdir new-project && cd $_
```

Finally, initiate the generator:

```
$ yo koa-socketio
```

## Start

Requires NodeJS >= v4.2.4


```
$ sh begin.sh &
```

## Test

```
$ npm test
```

See [**Koa Examples**](https://github.com/koajs/examples/)

## License
[Demo](http://game.feblogs.com:3000/)

[MIT License](http://en.wikipedia.org/wiki/MIT_License) @ addison