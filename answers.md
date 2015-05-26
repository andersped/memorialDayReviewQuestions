<h2>List and describe each of the primitive data types (number, string, boolean, null, undefined). What do they each represent?</h2>
The primitive data types are the types of data that javascript uses and interprets. <br>
	1. Number- a number is a numerical value that be either negative or positive. This type can be added, subtracted, divided or multiplied by other Numbers. <br>
	2. A string is a value that is inside quotation marks. A string can have numbers inside it but numbers cannot have strings inside them. A string is used to represent values that are not necessarily numbers and are defined in words.   
	3. A boolean value is a true or false statement. These are used to evaluate functions and data types within Javascript. The outcome is either true, false or undefined. Based on the outcome being true or false the outcome of the function can change. <br>
	4. Null is given if a function or the outcome is empty, meaning there is not object there. <br>
	5. Unlike null undefined is an object but has no value assigned to the variable. 

<h2>Explain what a variable is.</h2>
A variable is something that a value is given to it. It can represent a number, string or function. Once a variable is declared either in a function or on a global scale it can be resued. The difference is, if its declared within a function, its assigned value will only be applicable within that function. 

<h2>Describe in precise terms what’s happening with variable assignment using “var keyword”, “identifier”, “value”, “assign” etc…</h2>
1. With var keyword, that makes the variable equal to that keyword's value inside an object. 
2. With an identifier, the variable is equal to a string/name.
3. With a value, the variable is equal to a number and can be used as such. In this case it looks like a string but with the quotations as its representing a number.
4. When a variable is an assign, it is the outcome of the function and can be used as such. But each instance of the equation could be different so the variable can change in value. 


<h2>Evaluate the following expression: !(typeof(9) === typeof(9.5) && (99 == "99" || !true))</h2>
Its False && False, so the expression is false. 

<h2>Use a for loop to iterate through an array.</h2>
for (var i =0; i < array.length, i++);

<h2>Define functions using declarations and expressions.</h2>
Declaration would be Function Example(a){ return a}. Whereas expression are var x = function(a){ return a}


<h2>Articulate the difference between defining and invoking a function.</h2>
1. Defining a function is declaraing the function, passing through arguments and then having the function statments that declares what the function should do. 
2. Invoking a function is using a function as one of the arguments. This is typical in constructor functions in javascript when they are being used as classes. 

<h2>Describe how data flows into a function (by passing in arguments).</h2>
Data flows into the function by calling the function. This means to activate the function. In the sytax of activating the function you declare what the arguments are and they are passed through the function. They can be variables, strings, etc. 

<h2>Describe how data flows out of functions (by using the return keyword).</h2>
By using the return keyword, that return when you want to stop the function and use its output. The return declaration declares the output of the function. 


<h2>"Functions are just values" - explain.</h2>
Functions are used to create values. Those values can be numbers, strings, boolean values, etc. These values are then used in what appropriate for the program. 

<h2>Write functions that return values.</h2>
function mulitplie(a,b){ return a*b}; this is a function that takes 2 arguments, multiplies them together and returns that answer. 

<h2>Write functions that have side effects, such as logging to the console or manipulating DOM.</h2>
$("body").click(function(){ console.log("Clicked!")}); When the user clicks anywhere on the body of the page, the console will return "Clicked!"

<h2>Explain the difference between locally-scoped and globally scoped variables and write examples of each.</h2>
Localled scoped variables are variables declared inside a function and can only be called on inside that function. Whereas globally scoped variables can be used in any function. 
Locally: function multiple(a,b){ var one = a; var two = b; return one * two;};.
Globalley: var one= 5; var two= 10; function(one, two){ return one*two;};


<h2>Define ‘type coercion’ and identify instances when it occurs.</h2>
This happends when the operands of an operator are different types so one of them will be converted to that type. Its typical with boolean values when only == is used to compare rather than ===. So it can change a string into a integer if being compared with an integer. 

<h2>Explain what the DOM is. Where does it live? What is it for? How does it get created?</h2>
The DOM is the outline of the html and how its set up. It basically creates the model of how the html page is set up. 


<h2>Describe the CSS Box model. What 5 properties affect the box model?</h2>

<h2>What is the difference between relative and absolute poitions in CSS?</h2>

<h2>What is the difference between block and inline elements?</h2>

<h2>What does each git command do? git add ., git commit -m “”, git push origin master</h2>
Each one of these commands is involved in updating github or something relevant. Git add is adding those specific files you want to add to your shared project. git comm -m "" will give you the ability to comment on your new files. git push will then push up the files with your comments.

<h2>Git Branches: What are they? What are they used for?</h2>
Branches are different sections of a project that are being worked on so everything updates without missing certain pieces. 

<h2>What's the difference between git and github?</h2>

<h2>Identify all of the truthy and falsy values in JS and explain what it means to be “truthy” and “falsy”.</h2>

<h2>How do you access elements inside of an array?</h2>
You can acces them with an index. So and index is with square brackets and represents the position in which your call on in the array. So array[0], its the first element in the array and so on. 

<h2>What's the difference between arrays and objects?</h2>

<h2>How do you create arrays and objects?</h2>

<h2>How do you access values inside an object?</h2>

<h2>Describe the three components of a for loop.</h2>

<h2>Name three types of HTML mouse events.</h2>

<h2>What is event propagation?</h2>

<h2>What is npm?</h2>

<h2>What are npm modules? How do you install an npm module?</h2>

<h2>Describe the execution of a while loop and the potential for infinite loops.</h2>