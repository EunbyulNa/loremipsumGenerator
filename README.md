# lorem ipsum generator

# 1. How it works 
Choose how many random sentences you want to generate, then click the Generate button 
Even if you choose a negative number, it will generate random sentences. So don't worry about that! 

# 2. What I learned 
-Math.floor() : Round down and return the largest integer<br>
-Math.random() : Returns a random number from 0 up to but not including 1, can be used with Math.floor() to make random integers <br>
-Check whether the value is string or number : It is really important to check! <br>
In this project, the amount value from the input is actually String, not a number. So I need to change it to the number to use parseInt() method<br>
💡 Tip : You can see the different colors in the Chrom developer console, between 5(Number), "5"(String) <br>
-Template literals(Template strings) : It use back-ticks, (``). With ${...} you can interpolate variables and expressions into strings<br>
-slice(start, end) : Returns a shallow copy of all, or part of an array without modifying the original. <br>
Selected from start to end(end not included)
