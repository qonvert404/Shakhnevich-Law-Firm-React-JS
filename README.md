# Shakhnevich Law Firm React JS

<img src="https://shakhnevichlaw.herokuapp.com/6b0319b3b1a45f32a10179888d944ea0.png" width="900" height="100">

Shaknevich Law Firm is a modern Javascript Site based on React Components and Bootstrap 4 Framework

### Features

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
