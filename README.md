# dockeasy
super simple and easy to use docker CLI for purging, building, bootstrapping and deploying new containers

## installation

``` bash
  $ [sudo] npm install dockeasy -g
```

## Configure

Create a `Dockeasy` file inside the root directory of your app, this transforms your project into an easy docker build. Add the name and the app location and the rest is easy.  See example

    NAME example-app
    
    APP ./app/src/bin

Create your `Dockerfile` file and drop inside the root directory.  

You can download some example builds [here](link)

## Usage

Navigate to the build directory and start using `dockeasy`

     $ cd BUILD_DIRECTORY

### Purging

``` bash
  $ dockeasy purge
```

### Building

``` bash
  $ dockeasy build
```

### Bootsrap

``` bash
  $ dockeasy boot
```
