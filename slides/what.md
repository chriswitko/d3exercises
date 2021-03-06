## This session
### ~ What are we going to do ~


## Before we start
 
 - Get the code from: https://github.com/josdirksen/d3exercises
 - You need a webserver for some of the examples:
  - IntelliJ supports this (right click on HTML and run)
  - Easiest is with python: check if you can run:
    ```
     python -m SimpleHTTPServer (for Python 2)
     python3 -m http.server (for Python 3)
    ```

If not download the mongoose webserver, and you have


## Who am I
 
Love writing, and talking about technology (*frontend* as well as *backend*). Writing about stuff for Packt and Manning
    
 - Twitter: [@josdirksen]()
 - Github: [http://www.github.com/josdirksen]()
 - Contact me: [jos.dirksen@gmail.com]()
 - Blog at: [www.smartjava.org]()

Plug: **Expert Data Visualization with D3.js (Q1 2017)**


## What are we going to do
 
 - I'll introduce a subject (couple of minutes)
 - I'll Explain the exercise
 - You can fill in the blanks in the provided code.

 
```javascript
// Step 2. We can also select multiple elements. Use d3.select and
//         d3.selectAll to see the difference when selecting all the
//         <li> elements, and use either classed or attr to set the class
//         of these elements to 'step2'.

// d3.selectAll(...).classed(..., ...)
```

** * Halfway during the exercise I'll push an answer to git and Don't hesitate to ask questions!* **


## We're going to try and cover...

 - Learn how D3.js binds data to DOM elements.
 - Make basic charts and diagrams
 - Visualize hierarchical data 
 - Show connected graphs
 - Combine gis/geo information with opendata
 - Make art with voronois


## What aren't we going to cover

D3.js is big, very big. We'll explore the basics for data visualization, but 
there is a whole lot more. Most important stuff we skip:

 - User interaction, mouse events, drag events.
 - Animations
 - Zooming & dragging
 - Streaming data
 - loading and queue data
 - Typescript, ES6, Scale.js bindings
 - ...