# jsoxford grunt talk

These are the slides of my talk at JSOxford on 22nd May, 2013. To see them, skip to [Installation](#installation), install it on your local computer, and go.

## Installation

If you already have reveal.js set up, grab the `index.html`, and off you go.

TLDR version: use the full setup, and run as intended.

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features as well as the development tasks needed to make changes to the source.


### Full setup

Some reveal.js features, like external markdown, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
```
$ git clone git@github.com:hakimel/reveal.js.git
```

5. Install dependencies
```
$ npm install
```

6. Serve the presentation and monitor source files for changes
```
$ grunt serve
```

7. Open <http://localhost:8000> to view your presentation

## Acknowledgements

1. [@jsoxford](https://twitter.com/jsoxford) for organising everything.

2. [White October](http://www.whiteoctober.co.uk/) for hosting the event! (awsm job people!)

3. [Electric Studio](http://www.electricstudio.co.uk/) for letting me break things as I learn them. :)

4. [reveal.js](https://github.com/hakimel/reveal.js) for making the presentation a possibility