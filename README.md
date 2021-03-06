[![Build Status](https://travis-ci.org/lucasaugustofrontend/locadora.svg?branch=master)](https://travis-ci.org/lucasaugustofrontend/locadora)

# Project Locadora
> Desenvolvimento de uma pequena lista de filmes estilo locadora

## Stack Project
- Task Runner [Gulp](https://gulpjs.com "GulpJS")
- HTMl Template Engine [PUG](https://github.com/pugjs/pug "Template Engine Pug")
- CSS Preprocessor [SASS](http://sass-lang.com/ "Stylus")

## Folder Structure

    .
    |__ docs
    |   |__ assets
    |   |   |__ images
    |   |   |__ javascripts
    |   |   |__ stylesheets
    |   |__ index.html
    |__ src
    |   |__ assets
    |       |__ images
    |       |__ javascripts
    |       |__ sass
    |       |__stylesheet
    |       |__ views
    |       |   |__ include
    |       |   |__ layouts
    |       |   |__ partials
    |       |   |__ index.pug
    |__ .editorconfig
    |__ .eslint.json
    |__ .gitignore
    |__ .travis.yml
    |__ catalogo.json
    |__ CONTRIBUTING.md
    |__ gulpfile.js
    |__ LICENSE.md
    |__ package.json
    |__ README.md

## Run the project locally
**1 -** Prepare the enviroment
```sh
$ npm install -g gulp-cli
```
**2 -** Clone the project and install the dependencies:
```sh
$ git clone https://github.com/lucasaugustofrontend/locadora.git
$ cd locadora
$ npm install
```
**3 -** Run static server and livereload
```sh
$ gulp server
```

## Automatic Tasks
 - `$ gulp build`: Compile, concat and minify all files.
 - `$ gulp server`: Watch the files and build and start a static server.

## Contributing
Find on our [roadmap](https://github.com/lucasaugustofrontend/locadora/issues) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/lucasaugustofrontend/locadora/blob/master/CONTRIBUTING.md).

## License
[MIT License](https://github.com/lucasaugustofrontend/locadora/blob/master/LICENSE.md) © [Lucas Augusto](http://lucasaugustodesigner.com.br/)
