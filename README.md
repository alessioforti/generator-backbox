# generator-backbox

A modern website generator for [Yeoman](http://yeoman.io) used to scaffold and setup commoly used tecnologies and tasks.

It is backed with Webpack, Bootstrap 4, HTML5 Boilerplate and Jquery. 
It bundles and minifies CSS & JS.

This is a simple generator intended to be a base for your next project. Used as is can generate static pages to be published as they are or to be included in CMS template files. Could be expanded and customized with your npm packages to do more than that.
This is intended to be a continuation of the famous [Yeoman Webapp Generator](http://yeoman.io/learning)
Generator Backbox should be a starting point; of course there is room to improve and if you feel you'd like to contribute, I will be happy.


## Usage

Install the generator:

  ```
  $ npm install -g generator-backbox
  ```

Navigate to the folder where you'd like to scaffold your project and run the generator:

  ```
  $ yo backbox
  ```

Run npm `serve` task to launch a dev server with browser reloads on file changes.

  ```
  $ npm run serve
  ```
Run npm `build` task to build the project and output it in the `dist` folder.

  ```
  $ npm run build
  ```



## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)