##Coffee Script##
<hr>
*CoffeeScript is a little language that compiles into JavaScript.* Underneath that awkward Java-esque patina, JavaScript has always had a gorgeous heart. CoffeeScript is an attempt to expose the good parts of JavaScript in a simple way.
<br>
CoffeeScript is a compiler. It's meant to be more readable, and then it outputs 
<br>

###Java Script###

	square = function(x) { <br>
  		return x * x; <br>
	};<br>


	cube = function(x) {<br>
  		return square(x) * x;<br>
	};<br>
	

###Coffee Script###
	square = (x) -> x * x<br>
	cube = (x) -> square(x) * x
	<hr>


<ul>
<li>Coffee Script doesn't require braces and parentheses. </li>
<li>Mandatory indentation </li>
<li>-></li>
<li>White space sensetivity (be careful)</li>
<li>Poor documentation.</li>
</ul>
<br>
The golden rule of CoffeeScript is: "_It's just JavaScript_". The code compiles one-to-one into the equivalent JS, and there is no interpretation at runtime.
<br>
<br>
<br>
<br>
##Gulp##
<hr>
Task runner<br>

<br>
What's a task runner?
<br>
<br>
	Task runners are small applications that are used to automate many of the time consuming, boring (but very important) tasks that you have to do while developing a project. These include tasks such as running tests, concatenating files, minification, and CSS preprocessing. By simply creating a task file, you can instruct the task runner to automatically take care of just about any development task you can think of as you make changes to your files. It’s a very simple idea that will save you a lot of time and allow you to stay focused on development.