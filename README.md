# HTTP and Web APIs

* Anatomy of a Web Request ([slides](https://docs.google.com/presentation/d/12F814zTAxTzUkuLVLd9bUL4zo8PPklq6QHJdmuQBNJw/edit?usp=sharing))
* So, what's a web server?
  * A program that knows how to speak HTTP (i.e. receive and interpret HTTP requests, and send HTTP responses)
  * The `http-server` we use for testing is such a program.
  * Let's see this in the browser...
    * index.html, main.js, styles.css are all retrieved via HTTP
    * voter data CSV files
    * Mapbox map tiles
* An API server is just a web server built for a particular purpose.
  * E.g., data storage services -- like [Firestore](https://firebase.google.com/docs/web/setup)
  * E.g., Mapbox services -- like routing