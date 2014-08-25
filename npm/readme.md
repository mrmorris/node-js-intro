Node Package Manager NPM
========================
[Presentation (3,4)](https://docs.google.com/a/moonhighway.com/presentation/d/1BC3CrRWqiKvDYXU6y2_cVegLdZ9WMkYAXdR2OaJNIcI/edit#slide=id.g33becb33d_00)
The Node Package manager is where we get modules from the node js community.  Node modules hosted at github can
be registered here as well.  Once we find a module that we like, all we need is it's name.
[npmjs.org](https://www.npmjs.org/)

##Create A Package.json
```
    $ npm init
```

##Install a Node Module
```
    $ npm install module
```

##Save a node module to package.json
```
    $ npm install module --save
```

##Save a dev module to package.json
```
    $ npm install module --save-dev
```

##Install a global module
```
    $ npm install module -g
```

##List Global Modules
```
    $ npm list -g
```

node_modules
------------
Any node package that you install will be located in the node_modules folder.  You have access to the source right
within your project!

Package JSON
------------

###Package.json for Express
[Express Package.json](https://github.com/visionmedia/express/blob/master/package.json)
```javascript
    {
      "name": "express",
      "description": "Sinatra inspired web development framework",
      "version": "4.2.0",
      "author": "TJ Holowaychuk <tj@vision-media.ca>",
      "contributors": [
        {
          "name": "TJ Holowaychuk",
          "email": "tj@vision-media.ca"
        },
        {
          "name": "Aaron Heckmann",
          "email": "aaron.heckmann+github@gmail.com"
        },
        {
          "name": "Ciaran Jessup",
          "email": "ciaranj@gmail.com"
        },
        {
          "name": "Douglas Christopher Wilson",
          "email": "doug@somethingdoug.com"
        },
        {
          "name": "Guillermo Rauch",
          "email": "rauchg@gmail.com"
        },
        {
          "name": "Jonathan Ong",
          "email": "me@jongleberry.com"
        },
        {
          "name": "Roman Shtylman",
          "email": "shtylman+expressjs@gmail.com"
        }
      ],
      "dependencies": {
        "parseurl": "1.0.1",
        "accepts": "1.0.1",
        "type-is": "1.1.0",
        "range-parser": "1.0.0",
        "cookie": "0.1.2",
        "buffer-crc32": "0.2.1",
        "fresh": "0.2.2",
        "methods": "1.0.0",
        "send": "0.3.0",
        "cookie-signature": "1.0.3",
        "merge-descriptors": "0.0.2",
        "utils-merge": "1.0.0",
        "escape-html": "1.0.1",
        "qs": "0.6.6",
        "serve-static": "1.1.0",
        "path-to-regexp": "0.1.2",
        "debug": "0.8.1"
      },
      "devDependencies": {
        "mocha": "~1.18.2",
        "body-parser": "~1.1.2",
        "connect-redis": "~2.0.0",
        "ejs": "~1.0.0",
        "jade": "~0.35.0",
        "marked": "0.3.2",
        "multiparty": "~3.2.4",
        "hjs": "~0.0.6",
        "should": "~3.3.1",
        "supertest": "~0.12.0",
        "method-override": "1.0.0",
        "cookie-parser": "1.0.1",
        "express-session": "1.0.4",
        "morgan": "1.0.1",
        "vhost": "1.0.0"
      },
      "keywords": [
        "express",
        "framework",
        "sinatra",
        "web",
        "rest",
        "restful",
        "router",
        "app",
        "api"
      ],
      "repository": "git://github.com/visionmedia/express",
      "scripts": {
        "prepublish": "npm prune",
        "test": "make test"
      },
      "engines": {
        "node": ">= 0.10.0"
      },
      "license": "MIT"
    }
```


