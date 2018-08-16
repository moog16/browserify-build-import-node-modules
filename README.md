# browserify-build-import-node-modules

This is an example to illustrate that exporting ES5 modules works.


This project includes the node_modules already, so DO NOT `npm install` or `yarn`. Instead do:

```
yarn build;
```

* Notice this works!
* Open `bundle.js` and notice there are no `class`, `extends`, `Object.assign` operators.
* Open `./node_modules/@material/textfield/package.json` and notice that the `main` property is pointing to an ES5 file.

```
{
  ...
  "main": "./dist/mdc.textfield.js",
  ...
}
```

