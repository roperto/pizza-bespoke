# Bespoke

A presentation about presentation.

A meta-presentation.

Please read the version of this `README.md` in the `master` branch before starting.

# Viewing

Please view `src/index.html` file.
Please read the version of this `README.md` in the `master` branch before starting.

# Viewing

After building, just copy the `dist` directory and open the `index.html` file.

Google Chrome is recommended, but it should work on any modern browser.

## Development

Use the command `gulp serve`, it you launch and refresh your browser
as needed.

## Bulding

Use the command `gulp build`, it will build into the `dist` directory.

## Dependencies

First, ensure you have the following installed:

1. [Node.js](http://nodejs.org)
2. [Bower](http://bower.io) (see below)
3. [Gulp](http://gulpjs.com)  (see below)

If you get an error
`/usr/bin/env: ‘node’: No such file or directory`
run `sudo ln -s /usr/bin/nodejs /usr/bin/node`

Then, install dependencies and run the preview server:

```bash
$ sudo npm install -g bower
$ sudo npm install -g gulp
$ npm install
$ bower install
$ gulp serve
```
