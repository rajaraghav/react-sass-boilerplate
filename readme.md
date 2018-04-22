# react-sass-Boilerplate

Boilerplate code for getting started on a react+sass project.

# Node-react+sass-heroku is available [here](https://github.com/rajaraghav/node-react-herokuass-Boilerplate/).

## About setup

* sass 7-1 pattern.
* implemented using scss, but can be changed.
* build process consisting concat, auto-prefix, compress, compile operations.
* ./client/src/sass/main.scss gets compiled to ./client/src/App.css.
* node-sass watches for any change in file, i.e. changes take effect without reloading.

## Downloading/cloning and installing dependencies directions.

* download/clone repository by typing following command in terminal.

```
git clone -b master --single-branch https://github.com/rajaraghav/react-sass-boilerplate.git

//this would allow you to clone only the sass branch.
```

* open terminal.
* go to repo location, inside terminal window.
* start typing.

```
npm i //install client dependencies.
```

## Running Sass watcher and react concurrently

```
//inside repo directory run this command on terminal.

npm run startr

//open localhost:3000 in browser.
```

## Running react only, without watching/compiling sass.

```
//inside repo directory run this command on terminal.

npm start

//open localhost:3000 in browser.
```

## Building css files(optional)

```
//inside repo directory run this command on terminal.

cd client
npm run build:css

//find your files in ./client/css/
```
