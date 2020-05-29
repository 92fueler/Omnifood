# Omnifood web 
> ## modern web design with HTML5 and CSS3

##  Responsive Web design 
#### 1. Setting up the fluid grid for responsive web design
##### Three ingredients to responsive web design 
* fluid grid: all layout elements are sized in relative unites, such as percentages, instead of absolute units like pixels 
* flexible images: are also sized in relative unites 
* media queries: allow us to specify different CSS style rules for different browser widths 
##### How three ingredients are displayed in this project 
* set up fluid grid: Responsive Grid System from http://www.responsivegridsystem.com/ is used. Another common solution to grid system is Bootstrap. Once the grid system is in place, everything will be in rows. 
* set up the width of a row which is the only element in the project is in the absolute value in pixels 

#### 2. using media queries 

## CSS tricks in this project 
#### How to reset CSS stylesheet ?
#### How to center an element on the page ? 
```
.row {
    margin: 0 auto; 
}
```
#### How to make the image as high as the browser viewport ? 
* What is the viewport? The viewport is the user's visible area of a web page. 
```
header {
    background-image: url(img/hero.jpg);
    height: 100vh: 
}
```
* What does 100vh mean ? It means the height of this image is equal to 100% of the **FULL** viewport height. 
* How about viewport width? vw is used to represent a percentage of the full viewport width. 
#### How to make a vertically and horizontally centered box ? 
```
.hero-text-box {
    position: absolute;
    width: 1140px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```
* What does transform: translate(-50%, -50%) do? It translates the element to a half of its width to the left and a half of its height up.
#### How to make an image darker ? 
```
header {
    background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url(img/hero.jpg);
}
```
* Using linear-gradient here is like put extra layer over the image.
#### How to design buttons?
#### The 4 link states in CSS: link, visited, hover, active 
#### CSS3 transitions for small animations 
#### How to create a simple navigation ? 


## Optimzing and launching the website 
#### 1. How to create a favicon ? 
#### 2. performance optimization: site speed 
#### 3. basic search engine optimization (SEO)
