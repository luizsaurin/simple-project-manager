<h1 align="center"><strong>Simple project manager</strong></h1>

Web page for managing projects. It is able to create projects, validate creation inputs, drag and drop between ACTIVE and FINISHED status.

## **How to run**

Install npm packages

```
npm install
```

Run dev server

```
npm start
```

By default, it will run a server for development. To run using the production configuration, update the build script inside package.json to:

```
"build": "webpack --config webpack.config.prod.js"
```