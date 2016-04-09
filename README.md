# Website Performance Optimization
Udacity Front End Web Development - Project 5: Website Optimization
## Synopsis

This is my fifth of a series of projects through Udacity's **Front End Web Development** course, through which I have been reviewing web fundamentals including HTML5, CSS and JavaScript.  This project involves optimizing this online portfolio for speed.

## Files Optimized

* **index.html :** Embedded CSS in HTML, and called JS asyncronously when possible
* **views/js/main.js :** Enhanced for better page load and fps when scolling through pizza.html


## Instructions

1. Check out the repository
2. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

3. Open a browser and visit localhost:8080
4. Download and install [ngrok](https://ngrok.com/) to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ngrok http 8080
  ```

5. Copy the public URL ngrok gives you, which can be used with PageSpeed Insights.