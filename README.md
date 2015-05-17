# staticyoemantemplate
Description
===========
First Financial Bank static build



Requirements
------------
* Node
* NPM
* Grunt
* Ruby
* SASS

Folder Structure
----------------
```
/app            // Main static html template.
--/fonts          // Fonts.
--/images         // Images.
--/scripts             // jQuery used by styleguide.
--/styles           // Sass source.
--/fonts            // fontsFolder.
/dist            // folder created by using $ grunt build.
/node_modules     // Folder created when running $ npm install
/bower_components     // Folder created when running $ bower install
/test              // testing Javascript

```


Install node.js
---------------
Reference: http://nodejs.org/
Go to the node.js website and click the Install button.

Check to see if node.js installed properly...

```

$ node -v
```


Install grunt.js
----------------
Reference: http://gruntjs.com/getting-started#installing-the-cli

```

$ sudo npm install -g grunt-cli
```


Install bower
----------------
Reference: http://bower.io/#install-bower

```

$ npm install -g bower



Install node.js Dependencies / Modules
--------------------------------------
From within the cloned repository...

```
$ npm install
```


Install SASS
----------------------------
Reference: http://sass-lang.com/install
From within the cloned repository...

```
$ gem install sass
```

Using yoeman
------------------------
Reference: http://yeoman.io/learning/


Using browsersync
------------------------
Reference: hhttp://www.browsersync.io/



start the server to preview static pages
------------------------
install bower components: bower install
install nmp dependencies: sudo npm install

Preview an app you have generated (with browsersync).
$ grunt serve
or with more info on the terminal.
$ grunt serve --verbose 
$ grunt test
$ grunt build  //build the static site. Creates a dist folder for production.

```




