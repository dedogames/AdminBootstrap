[![N|Solid](http://gameudi.com/wp-content/uploads/2017/05/cropped-site.png)](http://gameudi.com/index.php/2017/06/01/curso-css/)

# Template Boostrap certification

This project is a template for build web applications

### Tools used
 
* Bower - Pakager manager.
* Bootstrap - great UI boilerplate for modern web apps
* node.js - evented I/O for the backend 
* Gulp - the streaming build system 
* jQuery - JavaScript library

### Installation

This templas has two config files, the first is package.json and bower.json, with these files a lot of dependencies will be installed on project folder, bellow has a commando on terminal to run start project 

```sh
$ npm install && bower install 
```

### Documentation
 

| Plugin | Url |
| ------ | ------ |
| Bootstrap | [http://getbootstrap.com/]  |
| Nodejs | [https://nodejs.org/] |
| Npm | [https://www.npmjs.com/] |
| Bower |[https://bower.io/] |
| Gulp | [http://gulpjs.com/] | 
| game to lean Flexbox | [https://flexboxfroggy.com/] | 


### Development

Other important file is gulpfile.js, that is a powerful manager task and to run from terminal any task is simple.

```sh
$ gulp task
```
Tasks created on gulpfile

 | Task | Action |
| ------ | ------ |
| cache:css | remove "./dist/css/style.css" |
| cache:js  | remove "./dist/js/ap.js" |
| sass | Task compile scss to css |
| html | Task minify html|
| js |Task minify js | 
| concat-js | Task concat js  |
| server | Task server local|


web-app folder structure  
=========================
N.b.: within vhost project folder structure

 * **public** 
  * {routerfile}.php 
  * font 
  * css 
  * img 
  * js 
  * themes 
     * {theme[x]} 
         * font 
         * css 
         * img 
         * js
         * licenses
         
```
javascript
// Core variables and mixins
@import "variables";
@import "mixins";
@import "custom";

// Reset and dependencies
@import "normalize";
@import "print";

// Core CSS
@import "reboot";
//@import "type";
@import "images";
@import "code";
//@import "grid";
//@import "tables";
//@import "forms";
//@import "buttons";

// Components
//@import "transitions";
//@import "dropdown";
//@import "button-group";
//@import "input-group";
//@import "custom-forms";
@import "nav";
//@import "navbar";
@import "card";
//@import "breadcrumb";
//@import "pagination";
//@import "badge";
//@import "jumbotron";
//@import "alert";
//@import "progress";
//@import "media";
//@import "list-group";
//@import "responsive-embed";
//@import "close";

// Components w/ JavaScript
//@import "modal";
//@import "tooltip";
//@import "popover";
//@import "carousel";

// Utility classes
//@import "utilities";
```


License
----

MIT



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
