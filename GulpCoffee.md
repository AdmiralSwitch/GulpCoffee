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



One noticable differences is that Coffee Script doesn't require braces and parentheses. 
<br>
<br>
<br>
<br>
<br>
##Gulp##
<hr>
Task runner