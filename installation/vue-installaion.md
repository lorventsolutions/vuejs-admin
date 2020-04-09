# Vue Installaion

Here are the steps to install **Vuejs-admin:**

**Note :** 

Make sure you have [nodejs](https://nodejs.org) installed in your system with minimum version `6.10.0`,

you can check installed version by running `node -v` command in terminal.

If you are having older version, please install latest version from [nodejs.org](http://nodejs.org/)

## 1\) Install Dependencies

Run the below command to get all the dependencies from package.json

`yarn`

## 2\) File Compilation

Run the following command to compile all the files.

`npm run dev`

## 3\) File Compilation with watchers

Run the following command to set watchers for files so that they compile as soon as you save any changes

`npm run watch`

## 4\)serve with hot reload at localhost:8080

The following command will create a local server at localhost:8080 with hot-module-replacement enabled, to reflect your changes in the browser without effecting the state of your application.

`npm run hot`

## 5\) File compilation for production

Run the following command to compile all files with minification for production.

`npm run production`

**Note**: when using "dev" "watch" or "production" make sure that your application is the root directory of the server.

If your files are being server from a sub folder in the server like `localhost/vue` then consider using the laravel-mix `mix.setResourceRoot('/');` option.

if you are serving the files like `localhost/vue` then set `mix.setResourceRoot('/vue/');`

Eventhough you can run `npm install` we suggest you to run `yarn install` since the package contains `yarn.lock` file which lets you get the exact version of packages that we have used.

