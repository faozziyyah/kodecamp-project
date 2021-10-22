# Kodecamp-Project

A responsive multipage website built with Bootstrap 5.0 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [The process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Additional](#additional)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- Navigate and view all pages

### Screenshot

![](images/Home.png)


### Links

- Solution URL: (https://github.com/faozziyyah/kodecamp-project/)
- Live Site URL: (https://faozziyyah.github.io/kodecamp-project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap 5.0
- Flexbox

### What I learned

- How to use carousel in Bootstrap 5.0

```HTML
<div id="carouselExampleCaptions" class="carousel slide d-block d-sm-block d-md-none" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img class="d-block w-100" id="img-2"  src="../images/image2b.png" />
                <div class="carousel-caption d-block d-sm-block d-md-none">
                  <h3>Serve our customers and always deliver the customer service </h3>
                  <p>We provide a full range of front end
                    machanical repairs for all makes and models of cars, no matter the cause. This includes.</p>
                </div>
              </div>

              <div class="carousel-item ">
                <img src="../images/image3.png" class="d-block w-100" alt="...">
                <div class="carousel-caption d-block d-sm-block d-md-none">
                  <h3>To be the world's most eader in automotive business solutions.</h3>
                  <p>We provide a full range of front end
                    machanical repairs for all makes and models of cars, no matter the cause. This includes.</p>
                </div>
              </div>

              <div class="carousel-item ">
                <img src="../images/image3.png" class="d-block w-100" alt="...">
                <div class="carousel-caption d-block d-sm-block d-md-none">
                  <h5>We value the service we provide and our loyal returning customersl</h5>
                  <p>We provide a full range of front end
                    machanical repairs for all makes and models of cars, no matter the cause. This includes.</p>
                </div>
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
```

### Useful resources

- [KodeCamp](https://www.youtube.com/results?search_query=kodecamp+team) - Web Development Course Resources
- [Bootstrap 5.0](https://getbootstrap.com/docs/5.0/components/carousel/) - Bootstrap 5 carousel components

## Additional
### To makes change to this project, clone this repo to your local machine
- After cloning the repo to our local machine, please do the following :point_down:
- git pull origin (update the repo on your local machine)
- git checkout -b name of your branch   e.g ft-blog or ft-about (to create your own branch)
- Add your codes
- After that, do git status(to check the changes you've made and be sure)
- Then git add .
- git commit -m "commit message"
- git push origin name of the branch you created e.g git push origin ft-about
- Thank you 

### Please take note
- All CSS files should be in the CSS folder 
- Javascript files in the Js folder
- Images in the images folder
- All HTML files in the pages folder except the home page(index.html)
