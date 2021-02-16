<h1 align="center">Projet FishEye</h1>

<div align="center">
  
</div>
<div align="center">
  <strong>Créez un site accessible pour une plateforme de photographes</strong>
<div></div>
<br/>
</div>

<div align="center">
  <!-- Last Commit -->
  <a href="#">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/audreydiez/AudreyDiez_6_16022021?style=for-the-badge">     
  </a>
  <!-- W3C  -->
  <a href="#">
    <img alt="W3C Validation" src="https://img.shields.io/w3c-validation/html?style=for-the-badge&targetUrl=https%3A%2F%2Faudreydiez.github.io%2FAudreyDiez_6_16022021">  
    </a> 
<!-- website  -->
  <a href="#">
   <img alt="Website" src="https://img.shields.io/website?down_message=Offline&style=for-the-badge&up_message=Online&url=https%3A%2F%2Faudreydiez.github.io%2FAudreyDiez_6_16022021%2F%23">
  </a> 
</div>

<div align="center">
  <h3>
    <a href="https://www.audreydiez.com">
      My Website
    </a>
    <span> | </span>
    <a href="https://github.com/audreydiez">
      My Github profile
    </a> 
    <span> | </span>
    <a href="https://audreydiez.github.io/AudreyDiez_6_16022021/#">
      The FishEye project
    </a>    
  </h3>
</div>

## Features
- __Vanilla code:__ No Bootstrap, no jquery, no Js Framework
- __CSS:__  SASS in 7:1
- __Javascript POO:__ Factory pattern used
- __Responsive:__ built for Desktop, tablet and mobile
- __Webpack ready:__ Package with SASS, ESlint, Babel-loader for JS compiler/transpiler
- __Commented:__ Yes !

## Global Object 
Here are some code.
```js
const test = "some js code";
```

## Installation
For Running on your machine :

Run `npm install`


## Command Line Utility
Configured in `'package.json'`, use following script for start hot reload server, build and push in `'gh-pages'` branch.
```js
"scripts": {
    "dev": "webpack --mode development",
    "start": "webpack serve --open 'Chrome'",
    "build": "webpack build",
    "deploy": "gh-pages -d dist"
  }
```