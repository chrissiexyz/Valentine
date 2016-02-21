## Valentine Aminated Message webpage

The project [Valentine Aminated Message webpage](http://chrissiexyz.github.io/valentine/) uses JavaScript to animate a name or a message. The codes were adopted from a course in Codecademy [Animate your name](https://www.codecademy.com/courses/animate-your-name/0/1).  

The repository include the following files:

* **index.html**: The main HTML document. Contains links to all of JS resources needed to render the animation, including main.js.
* **js/alphabet.js**: Contains code for formating the alphabet.
* **js/bubbles.js**: Contains function `drawName()`, `bounceName()`, `bounceBubbles()` and variable `bubbleShape` for animating the bubbles effect. 
* **js/main.js**: This is the code you need to modify to control what name/message you want to animate, what colors of your choices and what shape or bouncing effect you would like it to display.
* **js/jquery-1.10.2.min.js**: The jQuery library.
* **README.md**: The GitHub readme file.

### If you want to make changes...

In **js/main.js** file, you can define:

1.  variable of the message you want to animate, as in `var message`.
2.  variable for colors as the array letterColors, you can uncomment the color vector to make your own combination.
3.  control the shape of bubble by setting either `bubbleShape = "square"` or `bubbleShape = "circle"`, personally I think circle shape is cuter. 
4.  control the animation effect to be bounce the name or bounce the bubbles.
5.  More advanced changes are to make change in the **js/bubbles.js** file.

### If you have a similar project and want to use github to publish that webpage

I find this article useful to help me publish the webpage [Using Github Pages to Host Your Website](http://blog.teamtreehouse.com/using-github-pages-to-host-your-website)
