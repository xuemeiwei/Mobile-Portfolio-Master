# Website Performance Optimization Portfolio Project

This project is to optimize the online portfolio for speed by using techniques taught in this course.

## Tasks
### 1. Optimize PageSpeed Insights score for index.html
### 2. Optimize Frames per Second in pizza.html

## How to run the project
1. Download or clone the repository
2. Open index.html by using Chrome

## How to get the PageSpeed Insights score
1. Run a local server
```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
```
2. Make local server accessible remotely.
``` bash
  $> cd /path/to/your-project-folder
  $> \.ngrok http 8080
```
3. Go to website [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) and input the public URL ngrok gives you.

## Optimizations
1. For the optimization for the first task, there are following optimizations:
1) Remove the link to Open Sans fonts;
2) Add media = "print" for print.css;
3) Move js to the end of index.html;
4) Optimiza image files.

2. For the optimization for the first task, there are following optimizations:
1). Created a local vrailable to save randomPizzaContainer outside the loop, Moved the newwidth and dx variables out of the loop, Saved the array length

2). Moved the pizzasDiv variable outside the loop

3). Created local variables to save document.bodyscrollTop / 1250 outside the loop

4). Changed the generating pizzas part by changing document.getElementById("movingPizzas1");



