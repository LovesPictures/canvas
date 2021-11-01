##
# Project 4: CardioDay
Made with vanilla JavaScript

Judith Ricketts, Artist, Lecturer and Software engineer - [Contact](https://lovespictures.com/)  
Commit Date: 26th October 2021

## Guide

Javascript array methods are arrays forming a data structure containing list of elements which store multiple values in a single variable. The strength of JavaScript arrays lies in the array methods which are built-in functions we can apply to our arrays.  Each method has a unique function that performs a change or calculation to our array, saving having to write common functions from scratch.

![image](https://user-images.githubusercontent.com/25634451/139131376-f6266fd8-ceed-4380-9668-d396950ad84b.png)

<!-- elements -->
### long version of the code 
    const ordered = inventors.sort(function(a,b){
        if(a.year > b.year) {
              return 1;
       } else {
        return -1;
       }
    });    
    console.table(ordered);
<!-- elements -->
<!-- elements -->
### short verson or ternary version of the above code 
    const ordered = inventors.sort((a,b) => a.year > b.year ? 1 : -1);
    console.table(ordered);
<!-- elements -->    
    
## Approach

To use arrays to sortcut operations
 
## Useful links
* [The JavaScript Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) 
* [The JavaScript Array Handbook](https://www.freecodecamp.org/news/the-javascript-array-handbook/) 
* [A List of JavaScript Array Methods](https://medium.com/@mandeepkaur1/a-list-of-javascript-array-methods-145d09dd19a0) 


<!-- list of questions -->
<!--  // functional programming
using inline es6
what are an arrow functions - inline
what is a ternary operator - is a shorthand if statement 
waht is a DOM element 
what is a array spread  -->


<!-- A List of JavaScript Array Methods -->
<!-- guide  https://github.com/nitishdayal/JavaScript30 -->
<!-- formatting read.me https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax -->
