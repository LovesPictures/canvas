##
# Project 5: Canvas
Made with vanilla JavaScript

Judith Ricketts, Artist, Lecturer and Software engineer - [Contact](https://lovespictures.com/)  
Commit Date: 1st November 2021

## Guide

xx

## Approach

To use HTML5 canvass fundementals and vanilla JS to make an interactive drawing screen

![image](https://user-images.githubusercontent.com/25634451/139657132-5a30af57-cdb8-4d06-ab8c-5aa7d3ca92b2.png)

<!-- code example - tabulate -->
### event listener: mousemove

    canvas.addEventListener('mousemove', draw);
<!-- code example -->

![image](https://user-images.githubusercontent.com/25634451/139660180-5f66fbef-388c-458b-866e-93b6e8ce9543.png)
<!-- code example - tabulate -->
### update mousemove event listener  

        canvas.addEventListener('mousedown', (e) => {
          isDrawing = true; 
          // update
          [lastX, lastY] = [e.offsetX, e.offsetY];
        });
 
## Useful links
* [Basic usage of canvas - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage) 
* [25 Ridiculously Impressive HTML5 Canvas Experiments](https://code.tutsplus.com/articles/21-ridiculously-impressive-html5-canvas-experiments--net-14210) 
* [125 Open Source HTML5 Canvas Software Projects](https://opensourcelibs.com/libs/html5-canvas) 


<!-- list of questions -->
<!-- 
What is destructuring an array  - a shortened version of an array 
xx
xx

-->


<!-- A List of JavaScript Array Methods -->
<!-- guide  https://github.com/nitishdayal/JavaScript30 -->
<!-- formatting read.me https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
