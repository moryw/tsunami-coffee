# tsunami-coffee

CSS

html,
body {
  font-family: Helvetica, sans-serif;
  font-size: 16px;
  margin: 0;
  background-color: white;
}

.container {
  max-width: 960px;
  margin: 0 auto;
}

.main {
  background-image: url(https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-5/tsunami-coffee/images/bg-photo.png);
  background-size: cover;
  height: 30rem;
  padding-top: 1rem;
}

.main img {
  width: 15rem;
  display: block;
  margin: auto;
  margin-top: 5rem;
}

nav {
  background-color: OrangeRed;
  color: White;
}

ul {
  list-style: none;
  margin: 0;
}

li {
  display: inline-block;
  padding: 0.75rem 1.25rem;
}

.supporting,
.rating,
.gallery,
.location {
  margin: 4em auto;
}

.supporting {
  display: flex;
  align-items: flex-start;
  padding: 0 1rem;
}

.supporting img {
  height: 10%;
  width: 10%;
  margin-right: 5%;
}

.rating {
  background-color: OrangeRed;
  height: 20rem;
  padding: 0 1rem;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}

.rating h1 {
  font-size: 2.5rem;
}

.gallery img {
  display: block;
  width: 30%;
  margin: 1.5%;
  float: left;
}

.clearfix {
  clear: both;
}

.location {
  text-align: center;
  margin-bottom: 7rem;
}

.location img {
  width: 100%;
  height: auto;
}

footer {
  background-color: OrangeRed;
  padding: 0 1rem;
}

footer .container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5em 0;
  color: white;
}

@media only screen and (max-width: 960px) {
  .main {
    padding: 0;
  }
}

@media only screen and (max-width: 700px) {
  .supporting img {
    display: none;
  }
}

@media only screen and (max-width: 470px) {
  .rating h1  {
    font-size: 2rem;
  }
  .gallery img {
    width: 75%;
    height: auto;
    float: none;
    margin: 2.5% auto;
  }
  footer nav {
    display: none;
  }
  footer .container {
    justify-content: center;
  }
}







/* end css */
