# balanced.js #

Javascript client library for Balanced that tokenizes cards and bank accounts.

## Prerequisites ##

    node.js (version >= 0.8.0)

## Installation ##

    git clone git@github.com:nodesocket/balanced-js.git
    cd balanced-js
    npm install -g grunt-cli
    npm install

## Building ###

##### Both JS and Proxy #####

    grunt or grunt build

##### Just JS #####

    grunt build-js

##### Just Proxy #####

    grunt build-proxy

## Cleaning (deletes builds) ##

##### Both JS and Proxy #####

    grunt clean

##### Just JS #####

    grunt clean-js

##### Just Proxy #####

    grunt clean-proxy

## Running Example ##

Creates a node.js connect http web server and blocks, waiting for requests. Serves from `/build`.

    grunt serve-proxy

Then

    open ./example/index.html
