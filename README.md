My gulp Workflow
======================
A basic gulp workflow to compile sass, add vendor prefixes, minify CSS & JS and live reload with browser sync.

Works with HTML and PHP.

## Usage

1. Clone this repository

        $ git clone https://github.com/davidlpz/gulp-workflow.git

2. Change the directory to the application folder

        $ cd gulp-workflow

3. Start a new project

        $ npm init

4. Install the dependencies

        $ npm install gulp gulp-autoprefixer gulp-clean-css gulp-sass gulp-sourcemaps gulp-uglify gulp-rename browser-sync --save-dev

	To use with PHP also add

		$ npm install gulp-connect-php --save-dev

5. Run the `default` or `default-php`  task

        $ gulp default
        $ gulp default-php