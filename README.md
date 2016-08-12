### Setting up a productive environment for developing react apps

Watching any changes to the files
```
./node_modules/.bin/webpack -d --watch
```

#### Adding this configuration to your package.json file:
```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "dev": "webpack -d --watch",
    "build" : "webpack -p"
  },
```
Will allow you to run:
```
 npm run dev
```

And watch any changes in development mode.

Running
```
npm run build
```

will runs webpack in production mode and will minimize the bundle.js file

### installing new dependencies
```
npm i bootstrap bootstrap-loader -S
```
