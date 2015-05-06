# jekyll-gulp-sass-starter
A project starter kit for a Jekyll site using Gulp, Node-Sass, and BrowserSync.

Streamline your workflow with superfast Sass processing, Sass in the web inspector, minified and autoprefixed CSS output, and live auto-updating everything to multiple devices — from a single terminal tab!

##To Get Started
First install [Node JS](https://nodejs.org/) and [NPM](http://blog.npmjs.org/post/85484771375/how-to-install-npm). Homebrew makes this very easy, just type the following commands and you'll be good to go.
~~~
brew update
brew doctor
brew install node
~~~

Clone the starter kit repository:
~~~
git clone git@github.com:patrickgrady/jekyll-gulp-sass-starter.git
~~~

Navigate to the project folder:
~~~
cd into/the/repository
~~~

Now install the following npm packages locally:

[Node-Sass](https://github.com/sass/node-sass): Sass without the Ruby.
~~~
npm install node-sass
~~~

[BrowserSync](http://www.browsersync.io/): Multi-device auto-updates.
~~~
npm install browser-sync
~~~

[Gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md): A super flexible and customizable taskrunner.
~~~
npm install gulp
~~~

[gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer): Auto-prefixes CSS output so you don't have to.
~~~
npm install gulp-autoprefixer
~~~

[gulp-minify-css](https://www.npmjs.com/package/gulp-minify-css): Save those those kbs and we save ourselves.
~~~
npm install gulp-minify-css
~~~

[gulp-rename](https://www.npmjs.com/package/gulp-rename): Pretty self explanatory.
~~~
npm install gulp-rename
~~~

[gulp-sass](https://www.npmjs.com/package/gulp-sass): So Node-Sass works in gulp.
~~~
npm install gulp-sass
~~~

[gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps): See the Sass you wrote when you use the web inspector.
~~~
npm install gulp-sourcemaps
~~~

###Sweet Sweet Automation
A single word on the command line starts the build system and watches for changes:
~~~
gulp
~~~
