# Website Performance Optimization Project

## Description
The goal of this project was to optimize two webpages to run at 60fps by making changes to HTML, CSS and Javascript.

## Tools
Google Pagespeed was used to score the speed of the pages and
ensure that a load speed score of 90 or less was attained.

Chrome devtools were used to assess the beginning state of
the pages and identify bottlenecks and other places for improvement.

## Background
This project was developed by Benjamin Coate ([@bentocode](https://github.com/bentocode)) June 2017 as a requirement of the [Udacity Front End Web Developer Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001)

## Code Execution
Clone the repository and open index.html or views/pizza.html with a web browser to view the generated webpage.

## Log of completed changes

###  index.html

- Load images from local img folder
- Load fonts using javascript
- Minify files
- Make use of limited inline CSS
- Move scripts to end of the body element so they execute in an Idle period.
- Change external script loading to asynchronous

### pizza.html

- The function updatePositions() was updated so that layout calculation was made outside the for loop

- The function changePizzaSizes() was updated so that the geometric calculation of width was run once and with one example pizza.

