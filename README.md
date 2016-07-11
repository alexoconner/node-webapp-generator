# Simple node webapp generator/seed

This is a simple node seed for javascript based projects using es6 with babel.
The script minifies your html, compiles and minifies less styling and turns es6 code into code all the current browsers can understand.

## Install
* clone repository
* run ```npm install```

## Usage
* npm run build (for development)
* npm run make (minified for production)
* npm run watch (build on file change)

### Styles
This seed uses less and all files that need to be included should be imported into ```./src/styles/styles.less``` file.

### HTML
All html files that are stored in ```./src/html/``` will be moved (folder hierarchy included) into the dist folder.
