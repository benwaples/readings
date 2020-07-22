# Reading 12 summary

## Chart.js API
Interesting how people put the JS in the HTML? I wonder if this is common. This article covers the basics of importing Chart.js into HTML and manipulating the data with JavaScript. 

I like how easy Chart.js is and it really gives you a nice product for how easy it is. I wonder if it is common for API's like that to be free? How is that?

## Basic usage of `Canvas`
If you manipulate canvas with css, it distorts the image, where as manipulating it through the dom will scale it correctly. Fallback content is easy to set, so that old IE browsers can still see what is supposed to go there. Set fallback by placing text content between the `canvas` tags, or use an `img` tag there instead. 

I understand what is going on with the canvas, but I don't know what each exact line of code is doing. I think I would get it better if I made one from scratch.

## Drawing Shapes
`fillRect()` will create a rectangle and fill it with color
`clearRect()` creates a rectangle and clears all color
`strokeRect()` is just the border of a rectangle

strokes are bit more interesting:
`beginPath()` starts the stroke
`closePath()` makes a straight line from current position to the end
`stroke()` is the ...idk
`fill()` will fill your current shape. You don't need to close the patch before hand... it'll do it for you

the rest of the article combines these methods with others to create all sorts of shapes. Looks like there are a lot of shapes that it can create on top of being able to create anything with basic commands. 