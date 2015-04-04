# load-dependencies.js

A naive dependency loader to load scripts &amp; stylesheets on page load.

## Why does this exist?

I use this to package most of my work during development, when a build tool such as grunt concat + minify would slow-down development.

## Features

This script allows you to:

- Load stylesheets on page load
- Load stylesheets after page load
- Load scripts synchronously at page load
- Load scripts asynchronously at page load

You will notice that this does not attempt to be a full-featured javascript loader (such as require.js).

It is just a simple tool that can help you package your applications quickly.

## Usage

Open loader.js and follow the examples included. (They're commented out).

Several common libraries are included as examples from **CDNJS**, for your convenience.

You can rename this file to whatever you like.

Please note that URLs or paths should either be absolute, or relative to the path of your webpage, not the script loader itself.
