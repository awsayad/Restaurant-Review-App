# Restaurant Reviews App
---
## Overview: Restaurant Review App Stage 1

For the **Restaurant Reviews** projects, we converted a static webpage to a mobile-ready web application.
In **Stage 1**, The static design that lacks accessibility has been converted into a responsive design on different sized displays as well as accessible for screen reader use. we have also added a service worker to begin the process of creating a seamless offline experience for the users.

**Try Project Live** [Click Here](https://awsayad.github.io/Restaurant-Review-App/)

## How to launch the app locally?
To run this site, you'll need to use a local server. The easiest way to do so is to use the local http server using python. Please follow the steps mentioned below:

* Using Python HTTP server
* 1 -- Using Terminal enter into project directory
* 2 -- In a terminal, check the version of Python you have: `python -V`.
	- 3.a If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 3000` (or some other port, if port 8000 is already in use.)
	- 3.b For Python 3.x, you can use `python -m http.server 3000`.

* 3 -- With your server running, visit the site: `http://localhost:3000`

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). A token from [Mapbox](https://www.mapbox.com/) was used for the map. Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
