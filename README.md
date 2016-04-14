# Build an Express+Angular2 application with Babel

Most of the works for transpiling and including [Babel](https://babeljs.io/) is from [Shuhei](https://github.com/shuhei/)'s repository [babel-angular2-app](https://github.com/shuhei/babel-angular2-app)

However there's no testing included. Just [Angular 2](https://angular.io/), [Express](http://expressjs.com/).

## How it works

### Install

Clone/fork this repo and execute this command to update all the node modules dependencies :

```
npm install
```

### Build

Build only once to copy all needed angular js dependencies into dist folder and bundle all the js or application :

```
npm run build
```

Watch files for update & rebuild automatically:

```
npm run watch
```

### Start the server

```
npm run start
```

### Development

Folder ```client``` is for the client :
- ```client/app``` JavaScript files of the application, following basicly this convention
  - ```client/app/components``` for the Components
  - ```client/app/services``` for the Services
  - etc...
- ```client/templates``` The html templates of the Components
- ```client/css``` CSS files
- etc...

Folder ```server``` is for the server, build it like you always do (```server/app.js``` is the main entry point)


## Why do I did this boilerplate

I did this project mainly because it's a pain to configure the project and dependencies every time I want to start a new project with those technologies.

## Thanks

My thanks go to [Shuhei](https://github.com/shuhei/) for it's repo.

## License

[ISC](https://opensource.org/licenses/ISC)
