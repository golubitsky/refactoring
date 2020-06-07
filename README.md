* Builds are setup via [Travis CI](https://travis-ci.com/github/golubitsky/present) for the master branch.

* Builds generate static content in `/docs` based on `slides.md` .
* Builds deploy to: 

## Usage

Install reveal-md

``` 
npm install
```

then to serve and open the presentation in a browser

``` 
npm run presentation
```

or to generate a static website in the `docs` subdirectory

``` 
npm run generate
```

This presentation uses [reveal-md](https://github.com/webpro/reveal-md) which uses [reveal.js](http://lab.hakim.se/reveal-js)

[Based on this template](https://martinmurphy.github.io/slidestemplate)
