
# Learning Competencies
---------------------

# This blog should strengthen your understanding of

- JavaScript and its relationship to HTML and CSS
- Control flow and loops, arrays and objects
- Functions and why they are useful
- The DOM and DevTools



# An analogy to describe the differences between HTML and CSS

The more I read, observe others code, and play around with HTML, CSS, and JavaScript, the more I begin to truly see the amazing power that lies in these three technologies. HTML (Hyper Text Mark-up Language), CSS (Cascading Style Sheets), and JavaScript (also known as ECMAScript) are the 3 key, foundational tools one needs to understand to create amazing websites. 

When thinking of a way to describe HTML and CSS, I think of a trip to the Whitsunday's in Central Queensland. On this trip I went scuba diving at the great barrier reef. And when I think of the great barrier reef I think of 'Finding Nemo'. I see this large structure and framework of living coral, strong, sturdy, but adaptable. Then I see the various fishes, and sea creatures and plants that beautify the vast structure of the coral. Two separate things, but together they become one big living thriving organism. With structure, beauty and function.

Like the coral and sea creatures of the Great Barrier Reef, HTML and CSS are both very much separate technologies, but go hand-in-hand to create a truly marvelous collaboration of structure, functionality, and style. 

HTML provides the Semantic structure and meaning to the content of our website/web-app. This is done through the form of <tags>, these <tags> to inform other web technologies, frameworks, and languages the meaning of our information.   

CSS builds upon the structure of HTML to bring color and style to our HTML. This is done through the use of CSS Syntax. 

You have a selector ie a HTML <h1> tag followed by open a closed curly braces '{}', inside these curly braces we have a declaration which is made up of a property ie color, followed by a colon, followed by a value ie a color 'blue'. This selector and declaration is then interpreted by the browser to provide the color and style to our content.


# Explain control flow and loops using an example process from everyday life, for example 'waking up' or 'brushing your teeth'. (But not those ones).

In programming languages like Javascript, when we run the code, it is read from left-to-right top-to-bottom. In these languages we are able to use commands to manipulate the flow of how our lines of our code are utilized. In JavaScript and many other languages these are called loops. 

A loop allows us to re-use the same code time and time again to work through a problem. A typical loop is setup around a true-false conditional expression. If said conditional is true then run this line of code. 

We can think of this as driving our vehicle to work. We start off at home with a set distance to work say 20km, we can drive our car to the end of the drive way to the road and we have a conditional expression, is the distance to work to the left less than the the distance to work from the right. If this is true, then we turn left, if false then we turn right, we then have a counter set to the current distance to work. At each subsequent intersection we run the conditional expression. We will continue to run this series of conditional expressions until the distance to work is equal to 0. 


# Describe what the DOM is and an example of how you might interact with it.

The DOM (Document Object Model) is the browsers way of structuring the HTML mark-up, CSS, and JS in a away that the Browser understands, and then represents these values as a visual representation in the browser window, this is what you see when you enter 'www.google.com'. 

In the Browsers DevTools we are able to access and view the DOM within the browser window. In this we are able to select the specific CSS selectors and change them to represent a different value ie from 'blue' to 'green'. We can also use the DevTools and scripting files (ie JavaScript) to change how the content interacts through the use of 'DOM elements'. 

You could use these interactions in a away where you are adding an item to a list, JavaScript can manipulate the DOM to add an additional <div> with specific styling, and text content. JavaScript can also be used to delete an item in the same list. All of this is done without the webpage needing to be refreshed or reloaded.


# Explain the difference between accessing data from arrays and objects.

An Array is a collection of data types, for example:

- Strings: `'hello world'`
- Boolean: `true` `false`
- numbers: `256`

`let beautiful = ['blood', 'sweat', 'tears'];`

You can access a value inside the array through referencing it's index. Arrays use an index of 0 ie `array[]  

See example: `console.log(beautiful[2])` // returns `'tears'` 


An Object is accessed by calling it's property using two different syntaxes. Dot notation, and using `[]` square brackets.

`let object {`
    `property: 'value'`
`}`

Dot notation as follows:

let propertyValue = object.property // returns `'value'`

or with square brackets:

let propertyValue = object['property'] // returns `'value'`


# Explain what functions are and why they are useful.

Functions are reusable blocks of self contained code. 

Here is an example of a function syntax: 

`function getData() {`
  // do something;
`}`

Functions allow programmers to `write once, use multiple times`.

The code within the function can calculate simple mathematical equations, or can be used to process large amounts of data. 

Functions will typically receive the input of some data, and then return some data or value. These returned values could then be the input value for an additional function. 

Functions can be linked with other functions, and be used over and over again. 

Functions allow code files to be clean, and organised, easy to read and understand. 

