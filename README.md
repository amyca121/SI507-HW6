# JavaScript assignment

## Some useful resources
* Some [JavaScript tutorials](https://www.htmldog.com/guides/javascript/)
* The complicated [resources in the You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) series, including [your reading last week](https://github.com/getify/You-Dont-Know-JS/blob/master/up%20%26%20going/ch2.md)
* [A resource for CSS/style/colors](https://htmlcolorcodes.com/)  
* [An excerpt from a specific workshop site](https://witny-summer-guild-2018.github.io/day_4_exercise_2.html) (for a different audience than yourselves) which addresses some common questions about jQuery
* [The simple JSFiddle example from class](https://jsfiddle.net/2of65j8q/)
* A [W3Schools resource on JavaScript output](https://www.w3schools.com/js/js_output.asp)
* Google, Piazza, your classmates, office hours, lab time!

## Included files
* This `README.md`, which you should edit with answers to the questions
* `jsPracticeLab.html`, which you'll need to edit and try out
* `jquerylib_submit_example.html`, which you'll need to edit and try out

## Your goals for this lab

### Broadly
The aim for this lab is to practice adapting to and understanding code in a new-to-you (or not) language and its own libraries/packages -- JavaScript, in this case.

The programming skills you have built up till now are useful for *Python programming*, but, more than that, they extend to fundamentals of many kinds of programming.

This experience is *not in any way* about becoming an expert JavaScript programmer. Instead, it is about using what you *do* have experience with -- and your skills in *learning new things* that relate to programming -- in order to make educated judgments about some brand new-to-you code, even if you haven't learned in detail about it yet. That's part of what being in technology -- or even technology-adjacent -- will often mean.

### Specifically

Below are a bunch of questions and indications of things to do. For each indication of something to do with code, there is also an accompanying question to answer or brief explanation to give.

**To complete and submit this assignment, you should:**

* Fork (and clone) this repository
* Add our instructional team as a collaborator to your fork (see instructions for adding collaborators on Canvas)
* Edit this `README.md` file with answers to the questions/prompts, briefly, using Markdown formatting so that the questions appear in bulletpoints and the answers appear clearly below each respective question, *not* as bulletpoints.
* Add all names of those who worked on this (as indicated below)
* Make the changes that are indicated below to each of the `.html` files with JavaScript programs provided. (You'll probably do this concurrently with answering questions)
* Commit (as you go) and push your changes to all three files to your GitHub forked repository.
* Submit a link to your repository on Canvas. (This HW doesn't have an autograder -- it will be graded by hand/by humans this time.)

### Important notes
* You are *more than* welcome to work together on this, but **you must <u>each</u> submit a repo to be graded on it**, so if you do work together, you should do the following:
	* Make sure each one of you understands all the work -- YOU are responsible for using and knowing this information
	* Write each person's name & uniqname who worked on the assignment together on your submitted `README.md` file (you'll see a space for this below)

* In answering questions, please make sure the formatting is clear to read and that you have updated the names of everyone who worked with you, with your name first (see below).

* In answering questions, assume all of the questions include a *explain briefly* note -- you do NOT have to, and should not, write extended paragraphs. Be as concise as you can and explain in your own words. Don't worry about "whether it's enough" -- just worry about conveying your understanding so you can read it later, or even give it to someone else, and the answers will help/make sense.

* It is not acceptable to copy and paste answers from the internet and submit them as your own. If you cite things, make sure you provide a citation, including to links. If you get information from a resource and rephrase it so you're basically explaining an idea, that's just fine for an explanatory purpose in this assignment, but you *must* cite any quotes or examples that aren't yours.

* **For grading:** we are grading on...
	* Following the instructions
	* Approximate correctness of the code edits
	* Careful & clear answers to the questions
	* Correct answers to the questions
	* Slightly more than half the 1000 points will come from answering the questions. The rest will come from your edits to the code.

### Names of people you have worked with on this assignment
* List everyone's names and uniqnames who have worked on this assignment with you, **including your own name, but make sure YOUR name is first and bold**
* Like this:
* **Jackie Cohen (jczetta)**
* Yea-Ree Chang (cyearee)
* Ruchi Ookalkar (ruchido)
* Innocent Obi (innoobi)
* Zhen Wang (alejwang)
* etc.


* **Amy Carr (amyca)**

## Questions & code instructions

### The first questions address the `jsPracticeLab.html` file.

* **This is just an example question.**

This is what an example answer should look like. If you want to include some code, which you probably don't have to do, you can, like this:

```js
Some JavaScript code
```

* **What does a code comment look like in JavaScript? What character/s do you have to put before a comment?**

A code comment is indicated by two back slashes // causing the text to look lighter than the rest of the code.

* **Explain what needs to happen to get a JavaScript program to "run", given the JavaScript you've seen in this assignment.**

In order to run the javascript, the program has to know that you are writing javascript. So its important to write JavaScript within <script></script>.

* **What functions in JavaScript seem to be similar in function to the `print` function in Python? (There are two.) Why might you use one and not the other? Explain briefly.**

The functions console.log and alert seem to be similar to the function `print` in Python. The function alert acts more as a pop-up box while console.log is like debugging and it puts something on the web console. If you actually want something to render on the page, console.log is the better choice.
(https://www.w3schools.com/js/js_output.asp)

* **What code would have to comment out to get rid of the pop-up box when you load the page? (Related to the last question.) Do that in the code file, and then, add code so that a text box will appear that contains the current date and time! *HINT:* Look through the rest of the code first...**

You would have to comment out the `alert("hello")` code on line 12. Then you could replace it with `alert(new Date())`.

* **How can you put your own name at the top where it currently says "A name"? Explain very briefly how to do so, and replace `A name` in the web page with your own name.**

I made `document.querySelector('h1').innerHTML` equivalent to my name instead of "A name."

* **What does the word `document` represent in this code? Explain briefly.**

The word `document` represents the document being created by the html.

* **What is happening in line 12 (
		`document.querySelector('#items').innerHTML = document.getElementsByTagName('li').length`
)? Explain, briefly (<= 2 sentences).**

It looks like this line of code uses the document.querySelector to pull items from the document that have the prefix 'li', puts the items together and gets the length or the number of items. I think innerHTML updates the website based on inputs without having to refresh it.
(https://www.quackit.com/javascript/tutorial/innerhtml_in_javascript.cfm)
(https://www.w3schools.com/jsref/met_element_queryselector.asp)

* **What color would the background of this page be <u>if there were no JavaScript in this page</u>?**

The background color of the page would be white.

* **Why are there a couple of gray boxes on the screen with a different colored border? How could you edit this code to make them a different color? Explain briefly. Then edit the code to make those boxes some shade of blue, of your choosing.**

This code creates the gray boxes:
```<style>
p{
	background-color: #b3b3b3;
	border: 3px solid #FFFFFF;
	padding: 3%;
	font-size: 1.1em;
	line-height: 1.5;
	```
By replacing the `background-color` code with #0E0EE5 instead, I can change the color of the boxes from gray to blue.

* **Edit the code so that, if you highlight `McGill University` and copy it, you see the text `O Canada` near the bottom of the page. Briefly explain why you made the edits that you did -- how did you know/figure out what to do?**

I looked at the article below to understand how `oncopy` works. I then looked at how the oncopy function was set up for the University of Michigan. I realized that I needed to make sure that the program understood what function outcome went with what University that was copied. So I used the function code at the top of the page and copied it:

```function copyFunction(){
	document.querySelector('#cheer').innerHTML += "Go blue!<br>"
}
```
Then I changed the name of the function by adding a "2 at the end (copyFunction2) and changed the "Go Blue" to "O Canada" instead. Then I added the `oncopy="copyFunction2()">McGill University` under the "Some universities" code block. Below that I add the id "gill" to finish out the call to run the function.
(https://www.w3schools.com/jsref/event_oncopy.asp)

* **In the original code, when you click the button that says `Wow`, you see a text box! Wow. Explain briefly in your own words why the following code causes that to happen:**

```js
function handleClick(){
	alert("hello");
}
```
**and**

```js
<button onclick=handleClick() id="wow-button">Wow</button>
```
The code above causes that to happen because onclick is an event that calls on a previously established function `handleClick()`. The handleClick function creates the pop up box through an alert. Then a button is created that is identified as the `wow-button`. The button is set to contain the text "Wow." That way, the two code pieces are linked so that when someone clicks the button Wow, the "alert" action in the "handleClick" function produces a pop up text box.

* **Knowing what you learned from the previous question, add code/markup to the `jsPracticeLab.html` file *so that* there is a button with the text `Spring Equinox 2019` on it somewhere on the page, and when that button is clicked, a text box containing the text `March 20, 2019` appears. (There's no function -- that I am aware of -- to automatically get this info, you've got to type it yourself.)**

I copied the previous function:
```function handleClick(){
	alert("hello");
```
I then changed the function to handleClicks to create a new function and added the "March 20, 2019" in place of the "hello" text.

I then used this code:
```<button onclick=handleClick() id="wow-button">Wow</button>
```
I again replaced the function with handleClicks(), the "wow-button" with "equinox-button", and finally replaced the "Wow" with "Equinox 2019". This created a button with the text "Equinox 2019" on the website.


### The next few questions address the `jquerylib_submit_example.html` file.

* **Check out the file `jquerylib_submit_example.html`. This is an example of code that uses a package called `jQuery` (and this will need you to have an internet connection to run it properly, although the other file does not). Check out resources above for more on jQuery!**

* **When you enter input that isn't valid, you see an error that is red. Why is the error in red? Why is the response for valid inputs blue?**

The error is red because because of the code near that top of the file that indicates:
```.error{
		color: red;
}
.good {
		color: blue;
}
```
Later on in the code an if/else statement is set up in which a currentValue is tested against the valid and expected currentValue. If the tested value `== false`, The class is indicated as an "error" and shows the text `Not Valid!`. Indicating it as an error references the code above that causes the error text color to be red. The following else statement is indicated as "good" and so returns the text `Nice!` in the color blue indicated in the previous code as well.

* **What is this line `var regex = /^[a-zA-Z]+$/;` helping with? And if you googled something to figure that out, what did you google, and what, briefly, did you learn? (If you didn't need to google, you can leave that out, but explain briefly what that line is helping the program do, anyway.)**

I googled this question by searching the exact code and found a stack overflow discussing it. It said that when the carrot is outside the character class it notes a "begins with" operator, so anything that beings with a-z or A-Z. If it is inside the character class it negates it. I think this means that for something to be valid it has to start with a-z or A-Z (it has to start with a letter)
(https://stackoverflow.com/questions/2790813/regular-expression-a-za-z-or-a-za-z)

* **What's different about the syntax of conditional statements in JavaScript, compared to Python?**
The conditional statements in JavaScript are if, else if, and else. In python else if is identified as elif. Otherwise it appears that the conditional statements are used in pretty much the same fashion.
(https://www.w3schools.com/jsref/jsref_if.asp)

* **What do you think the `10000` refers to in the code `.fadeOut(10000)`?**

10000 is used to set the duration of time it takes for the code to fade out (slowly disappear). I think it might be that it sets the code to take 10000 milliseconds fade out rather than right away.
(https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_eff_fadeout_fadein)

* **What do you think is going on with the following code at the beginning of the program? Note that the most important thing to do for answering this question is to be thoughtful and clear, not to be absolutely correct:**

```
js
$(document).ready(function(){
    $("form").submit(function(event){
```
The `(document).ready (function()` part of the code makes the function available once the document has been loaded. The `("form").submit(function(event))` part of the code triggers when the form is submitted. It is used to either validate the form before sending it to the server or abort it. I think this has to do with people inputing one word only into the text box and hitting submit. By submitting it the form is checking to validate based on the parameters of the code below. For the part of the code that is not valid there is a event.preventDefault that will stop the form from being submitted.  
(https://www.tutorialspoint.com/What-is-document-ready-method-in-jQuery)
(https://javascript.info/forms-submit)

* **Add some code to the `jquerylib_submit_example.html` file so that, if the input is valid and is specifically the text `hello`, rather than the visible output being `Nice!` in blue, the visible output should be `Hello to you too!`, also in blue, just like `Nice!` is.**
	* *HINT:* You'll have to make some changes to the conditional statement, and possibly look up some JavaScript conditional syntax. You'll also need to look carefully at what generates visible output right now.

Based on the way conditional statements work, I decided to add an `else if` statement in between the original if and else statements in the code. That way if the word is not valid that will be tested and show first. The program then will check to see if the word is specifically the text "hello". If it is, it will print out "hello to you too." I based this `else if` code on the `else` code already written. After some issues, I realized I had to add `(currentValue == "hello")`, like the `if` statement above, to specify to the program what to look for. I then used the `$("#result").html('<p class="good">Nice!</p>').show().fadeOut(10000);` code from the original else statement, replacing "Nice!" with "Hello to you too!" I left the `class="good"` because that determines the color of the text and we want the text to be the same blue color as the "Nice!" returned by the `else` statement.
(https://www.w3schools.com/js/js_if_else.asp)
