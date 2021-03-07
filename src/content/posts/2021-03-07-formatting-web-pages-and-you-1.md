---
template: blog-post
title: "Formatting Web pages and you. "
slug: /formatting-web-pages
date: 2021-03-07 15:22
description: |-
  https://www.w3schools.com/html/html_responsive.asp  

  https://web.dev/responsive-web-design-basics/  

  https://www.invisionapp.com/inside-design/examples-responsive-web-design/  

  https://kinsta.com/blog/responsive-web-design/  
featuredImage: /assets/magic-leap-responsive-web-design.png
---
<!--StartFragment-->

When creating a webpage, regardless of its looks, the cool tricks you implement, or even the colors and pictures you set up, none of it will matter if it is not formatted correctly. Formatting a webpage or, more specifically, Responsive Web Design (RWD) is making sure that your website is formatted so that it automatically adjusts for different screen sizes and viewports so it can look good on any device. RWD is essential to know how to do and how to do it correctly; you will want your web page to look good on any device, you don't want it to look too small on a smartphone, not fit the size of a tablet, and have everything be scattered on your computer. RWD has multiple building blocks, but we will be looking at CSS and HTML, Fluid layouts, Media Queries, and Speed. These four topics are important for an RWD and will most likely spend most of your time on coding. 

First, we are looking at CSS and HTML and what is needed to make an RWD. HTML is the structure for the webpage it's what will create the layout and give it a basic look. CSS is the style and design; it will edit the design and the layout of the HTML code. You will need to know the basic structure for the website set and need the CSS to customize the look and, more importantly, the layout. CSS will allow set the layout of different web page formats. It will use media queries. 

Media queries are the fundamentals of creating an RWD; they allow you to set custom resolutions and screen sizes. They do this by using this code right here. 

<!--StartFragment-->

```css
@media screen and (min-width: 780px) {
.full-width-img {
margin: auto;
width: 90%;
}
```

<!--EndFragment-->

This code tells the web page that it wants widths below 780px to take up 90% of the screen's width. The code is fundamental in creating an RWD; it will allow you to set the screen sizes you want to fit on any device; all you need to do is change the min-width: to the pixel amount you want cover. 

More is needed for an RWD to function correctly. Although media queries set the size to edit the web page, you still need to edit them; you will need to set up fluid layouts and more. A fluid layout is designing your website to use dynamic values like percentages to set pictures, paragraphs, and more on the screen. A few things go into fluid layouts, like flex boxes, grid layout, and multiple-column layout. Let's start with flex boxes; a flexbox is used for setting items of different sizes to fit in a row of rows, with smaller items taking less space and bigger ones being allowed more. This allows for better positioning of items on smaller devices like smartphones and lets you customize where they go. The code for flex boxes is right here. 

<!--StartFragment-->

```css
.items {
  display: flex;
  justify-content: space-between;
}
```

<!--EndFragment-->

Next is grid layout; grid layout creates a grid for the user to set up items within. Instead of giving percentages, you would instead make a grid and put items on the grid. A code example for this is 

<!--StartFragment-->

```css
.container {
  display: grid;
  grid-template-columns: 1fr 3fr;
}
```

<!--EndFragment-->

The display is setting to grid, and the grid template- columns are telling the container to be set at 1fr, 3fr on the grid. Grid layouts cod also make gird layouts top allow as many items as possible to fit; the available number of tracks will shrink automatically as the screen size gets smaller. Lastly, there's the multi-column layout; it creates a responsive number of columns with column-width. It will add more columns if need. 

Lastly, we have speed. Speed is one of if not the most important thing for a web page to have. It's what keeps people on the site and might make them stray away. If the site is too slow, no one will want to go back to it. There are some ways to make your web page faster; you can optimize your images using a more efficient CSS layout, avoid render-blocking JS. Regardless of what you do, you need to have a fast and efficient website. 

To make RWD, you need to have a good number of elements to work with; you need to know how to work with HTML and CSS to implement the code needed. Media Queries to set the screen size to make changes to. Fluid layouts to set the screen layout along with flexbox's, multi-columns, and grid layouts. Finally, speed to make sure your website is fast and efficient. 

<!--EndFragment-->