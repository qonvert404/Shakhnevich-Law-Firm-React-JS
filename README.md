# Shakhnevich Law Firm React JS

<img src="https://i.ibb.co/QYDmM6T/logo.jpg" width="300" height="300">

Shaknevich Law Firm is a modern Javascript Site based on React Components and Bootstrap 4 Framework

## Table of contents
* [General info](#general-info)
* [Features](#features)
* [Screenshots](#screenshots)
* [Getting Started](#getting-started)

## Features

* Bootstrap 4.3+
* Form to Email Services
* Redux
* React Router 4
* ES6+
* React Router Dom 5.0.0
* Webpack
* Babel
* Google Fonts
* Google Maps
* Sass(.scss)
* Heroku

## Screenshots
![Home Page](https://i.ibb.co/dQz7djS/Screen-Shot-2019-09-10-at-5-04-25-PM.png)

## Getting Started

### Prerequisites

* [Node and npm](https://www.npmjs.com/get-npm)

### Installing

1. Clone this repo, `git clone https://github.com/KonstantinSavinov/Shakhnevich-Law-Firm-React-JS.git `
2. Go to project's root directory, `cd Shakhnevich-Law-Firm-React-JS`
3. Run `npm install` to install dependencies
4. Run `npm start` to start the test application (running on port 8080)
    
#### *Optional 
1. Setup your first [FormCarry](https://formcarry.com/documentation/getting-started) to send forms to email services
* Copy the form endpoint from your FormCarry account and paste it to `index.js` file that can be found by the path: `src/components/Form/`

```javascript
_axios.default.post("https://formcarry.com/s/XXXXXX"),
```
2. To use the [Maps Embed API](https://developers.google.com/maps/documentation/embed/get-api-key) you must have an API key
* Copy the API key from your Google Cloud Platform Console account and paste it to `index.js` file that can be found by the path: `src/components/GoogleMaps/`

```javascript
googleMapURL: "https://maps.googleapis.com/maps/api/js?key=--YOUR-KEY-GOES-HERE--&libraries=geometry,drawing,places",
```
