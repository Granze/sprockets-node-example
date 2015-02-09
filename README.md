# Sprockets-Node Example

An example Rails app showing how to integrate Sprockets with a Node.js-based asset
pipeline, using Browserify.

## Installation

First, clone the repo somewhere locally:

    $ git clone git@github.com:spikebrehm/sprockets-node-example.git

Then, run `bundle install` and `npm install` to install Ruby and JavaScript dependencies:

    $ bundle install
    $ npm install

Now you should be able to to run the Rails server:

    $ rails server

Check out the app running at `http://localhost:3000`.

## Usage

This Rails app is a simple implementation of the [TodoMVC Backbone app](https://github.com/tastejs/todomvc/tree/gh-pages/examples/backbone).

![screenshot](https://s3.amazonaws.com/f.cl.ly/items/1e1x1s1t3N0i3N213t1T/Screen%20Shot%202015-02-09%20at%208.41.45%20AM.png)

We've implemented two different versions of the TodoMVC Backbone app:

1. The default TodoMVC code, using Sprockets to manage the JavaScript assets (`http://localhost:3000`).
2. The TodoMVC code refactored to use CommonJS to manage the JavaScript assets (`http://localhost:3000/commonjs`).

Check out the `lib/browserify_template.rb` file and `script/assets/*.js` files for
the good stuff.
