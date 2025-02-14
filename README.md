![Image of Logo](templates/logo.jpg)

# Smart India Hackathon 2020
Textile Detection from CCTV Surveillance Videos

# Table of Contents

* [Description](https://github.com/amurto/gearstalk#description)
* [Dependencies](https://github.com/amurto/gearstalk#dependencies)
* [Installation](https://github.com/amurto/gearstalk#installation)
  * [Prerequisites](https://github.com/amurto/gearstalk#prerequisites)
  * [Instructions](https://github.com/amurto/gearstalk#instructions)
* [Usage](https://github.com/amurto/gearstalk#usage)
* [Contributors](https://github.com/amurto/gearstalk#contributors)
* [License](https://github.com/amurto/gearstalk#license)

# Description

The system focuses on capturing and saving various attributes of fabrics worn by targeted persons captured from various CCTV cameras through distributed intelligence along with time and location stamps over the period in a database. The database is compiled to be used in identification of suspects from video clips of crime related CCTV footages captured in a series of CCTV cameras located on routes and close to scene of crime.

## Objectives
* To Collect Image Dataset for Indian fabrics. 
* To Train our Machine Learning models for classifying the fabric labels from the video footages frame by frame.
* To design a system Architecture for processing Video footages from CCTV.
* To Store the Identified labels and respective timestamp in a database for the processed video footages.
* To provide an user friendly interface for the operator to perform video forensics and reporting.
* To Design the entire system in a more robust manner.

## Pros
* Responsive Web App Development
* Scalable Architecture
* Rich UI – UX Design
* Crop Image Search
* Reporting and Analytics
* Dockerization of Server Script
* Asynchronous and Non blocking Request Handling
* High Availability and Failover Architecture 
* Geolocation and MapBox
* Continuous Integration and Deployment Pipeline
* Cross-Platform Development using Electron.js
* Processing of Live feeds from CCTV
* Prepared 23 Labels for Indian Fabrics
* Video Quality Enhancement tools
* Easy storage and retrieval of large footages and Metadata
* Use of OpenSource Technologies
* Speech Recognition
* Use of Inhouse Developed APIs
 
## Screenshots
![Image 1](templates/img1.jpg)
![Image 2](templates/img2.jpg)

## Architecture
![Architecture](templates/architecture.jpg)

## Labels
![Labels](templates/labels.jpg)

# Dependencies

* [TensorFlow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [npm](https://www.npmjs.com/)
* [React.js](https://reactjs.org/)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Material UI](https://material-ui.com/)
* [amCharts](https://www.amcharts.com/)
* [MongoDB](https://www.mongodb.com/)
* [TypeScript](https://www.typescriptlang.org/)
* [Mapbox](https://www.mapbox.com/)

# Installation

### Prerequisites

* Install Node.js, npm, Python 3.8, MongoDB and TypeScript using the link above. Follow instructions on their respecive websites. Npm is included with Node.js.
* Get the API keys for Mapbox, RabbitmQ, MongoDB Cloud and fill out the environmetn variables.

### Instructions

Clone the repository
```bash
git clone https://github.com/amurto/gearstalk.git
```

Install all the dependencies on frontend
```bash
cd frontend
npm install
```

Install all the dependencies on both backend servers
```bash
cd backend
npm install
```
```bash
cd backend_2
npm install
```

# Usage

Run the flask server on port 5000
```bash
cd frontend
npm start
```

Run the frontend server on port 3000
```bash
cd frontend
npm start
```

Open a web browser and go to
```bash
http://localhost:3000
```

# Contributors

* Amurto Basu [@amurto](https://github.com/amurto)
* Carol Sebastian [@carol80](https://github.com/carol80)
* Sherwin Pillai [@sherwinpillai](https://github.com/sherwinpillai)
* Mahesh Desai [@mahesh131998](https://github.com/mahesh131998)
* Shubham Bhate [@ssb2920](https://github.com/ssb2920)
* Cassia Vaz [@CassiaVaz](https://github.com/CassiaVaz)

# Mentors
* Mahendra Mehra [@mahendra-mehra](https://github.com/mahendra-mehra)
* Elvis Dsouza [@ejson03](https://github.com/ejson03)

# License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[MIT License Link](https://github.com/amurto/gearstalk/blob/master/LICENSE)