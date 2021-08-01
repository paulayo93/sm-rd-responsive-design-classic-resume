<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
=======
>>>>>>> c689f6b... setup base project structure
<div align="center">
  <br />
  <br />
  <img src="https://res.cloudinary.com/bahdcoder/image/upload/v1616511796/Software_mentor_logo_1_1_1_xutgsi.png" width="450px">
</div>

<br />
<br />

<div>
<h1>Use BEM to define the structure CSS and variable declaration</h1>
<p>block__element--modifier</p>
</div>

<div align="center">
  <h3>
    <strong>
    Upgrade your software skills with practical real-world projects
    </strong>
  </h3>
  <p>The fastest and most effective way to master in-demand skills for your career 🚀. </p>
</div>

<br />

<div align="center">
  <h3>
    <a href="https://softwarementor.io">
      Website
    </a>
  </h3>
</div>

<div align="center">
  <sub>Built with ❤︎ by <a href="https://github.com/bahdcoder">Kati Frantz</a>
</div>
<<<<<<< HEAD
=======
# Front-end Webpack Boilerplate

## Managing assets ##

### Define Package

* Amend `package.json`
    * Specify your project package name.
    * Specify your project package version.
    * Specify your project package description.
    * Specify your project package repository url.
    * Specify your project package license.
* Configure `webpack.config.js`
    * Define at the beginning of the file the server path to your WordPress Installation
```js
const localServer = {
  path: 'localhost/',
  port: 3000
};
```

### Assets Source

* _SASS_ files are located under `/src/scss/`
* _JavaScript_ files with support of _ES6_ files are located under `/src/js/`
* _Images_ are located in `src/images/`
* _Fonts_ are located in `src/fonts/`

### Build Assets

* Execute `npm install`
* Execute `npm run build`
* Enable source files watching `npm run watch` (*Define any other files that needs syncing in `files:[]` section under `BrowserSyncPlugin` in `webpack.config.js`)
* Optimize assets for production with `npm run production`

### Processed Assets

* _CSS_ files are located under `/dist/css/`
* _JavaScript_ files with support of _ES6_ files are located under `/dist/js/`
* _Images_ are located in `dist/images/`
* _Fonts_ are located in `dist/fonts/`
>>>>>>> d9b20bc... Initial commit.
=======
>>>>>>> c689f6b... setup base project structure
=======

# Responsive Web Design


## Setup Font

The What, The why, The How, 


```css


@font-face {
    font-family: 'Poppins';
    src: url("../fonts/Poppins-Regular.eot?") format("eot"),
    url("../fonts/Poppins-Regular.woff") format("woff"), 
    url("../fonts/Poppins-Regular.ttf") format("truetype");
    font-style: normal;
    font-weight: 400;
  }
  


  @font-face {
    font-family: 'Poppins';
    src: url("../fonts/Poppins-Bold.eot?") format("eot"),
    url("../fonts/Poppins-Bold.woff") format("woff"), 
    url("../fonts/Poppins-Bold.ttf") format("truetype");
    font-style: normal;
    font-weight: 700;
  }

  

  @font-face {
    font-family: 'Poppins';
    src: url("../fonts/Poppins-Black.eot?") format("eot"),
    url("../fonts/Poppins-Black.woff") format("woff"), 
    url("../fonts/Poppins-Black.ttf") format("truetype");
    font-style: normal;
    font-weight: 900;
  }

```
>>>>>>> 6c81339... setup font-face
=======
>>>>>>> 8939458... Basic Font  Setup
