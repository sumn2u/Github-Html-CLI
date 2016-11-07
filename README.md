# Github-HTML-CLI

This is a super simple command line module that creates a new github project along with HTML5 boilerplate.

_Works on Macs / linux or things that have `pbcopy`_

```bash
$ github-web <github repo>
```

When you run a repo gets created in the logged in account along with the html file:

```HTML
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <title>Title</title>
    <link rel="icon" type="image/png" href="favicon.png">
    <link rel="stylesheet" href="assets/style.css">
  </head>
  <body>

  </body>
</html>
```



**You can [use it](#use-it) as-is or [adapt it](#adapt-it) to your own boilerplate needs**

## Use it

_You'll need [Node.js](http://www.nodejs.org) and [NPM](http://www.npmjs.org) (which comes when you install Node.js) on your computer._

Install `github-web` globally on you computer with NPM:

```bash
$ npm install -g github-web
```

From any terminal window, run the `github-web <repo-name>` command to get the boilerplate copied to you clipboard.

```
$ github-web <repo-name>
```

Then paste it where you want it. Done!

## Adapt it

_You'll need [Node.js](http://www.nodejs.org) and [NPM](http://www.npmjs.org) (which comes when you install Node.js) on your computer._

Clone this repository (or a fork of it) to your computer:

```bash
$ git clone git@github.com:sumn2u/Github-HTML-CLI.git
```

```bash
$ cd Github-HTML-CLI
```

Link this version to your system so that Node uses it when you run `github-web`. From inside the `Github-HTML-CLI` directory link it:

```bash
$ npm link
```

Then run `github-web <repo-name>` from any terminal window. Yay!
