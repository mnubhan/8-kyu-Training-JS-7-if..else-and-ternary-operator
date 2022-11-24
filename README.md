# 8-kyu-Training-JS-7-if..else-and-ternary-operator
https://www.codewars.com/kata/57202aefe8d6c514300001fd/train/javascript
<br>
In JavaScript, if..else is the most basic condition statement, it consists of three parts:condition, statement1, statement2, like this:
<br><br>
if (condition) statementa
<br>
else           statementb
<br><br>
It means that if the condition is true, then execute the statementa, otherwise execute the statementb.If the statementa or statementb more than one line, you need to add { and } at the head and tail of statement in JS, to keep the same indentation on Python and to put a end in Ruby where it indeed ends.
<br><br>
An example, if we want to judge whether a number is odd or even, we can write code like this:
<br><br>
function oddEven(n){
<br>
  if (n%2==1) return "odd number";
<br>
  else        return "even number";
<br>
}
<br><br>
If there is more than one condition to judge, we can use the compound if...else statement. an example:
<br><br>
function oldYoung(age){
<br>
  if (age<16)      return "children"
<br>
  else if (age<50) return "young man"   //use "else if" if needed
<br>
  else             return "old man"
<br>
}
<br><br>
This function returns a different value depending on the parameter age.
<br><br>
Looks very complicated? Well, JS and Ruby also support the ternary operator and Python has something similar too:
<br><br>
condition ? statementa : statementb
<br>
Condition and statement separated by "?", different statement separated by ":" in both Ruby and JS; in Python you put the condition in the middle of two alternatives. The two examples above can be simplified with ternary operator:
<br><br>
function oddEven(n){
<br>
  return n%2==1 ? "odd number" : "even number";
<br>
}
<br>
function oldYoung(age){
<br>
  return age<16 ? "children" : age<50 ? "young man" : "old man";
<br>
}
<br><br>
Task:
<br>
Complete function saleHotdogs/SaleHotDogs/sale_hotdogs, function accept 1 parameters:n, n is the number of customers to buy hotdogs, different numbers have different prices (refer to the following table), return a number that the customer need to pay how much money.
<br>
number	price (cents)
<br>
n < 5	100
<br>
n >= 5 and n < 10	95
<br>
n >= 10	90
<br><br>
You can use if..else or ternary operator to complete it.
<br><br>
When you have finished the work, click "Run Tests" to see if your code is working properly.
<br><br>
In the end, click "Submit" to submit your code pass this kata.
Series:
( ↑↑↑ Click the link above can get my newest kata list, Please add it to your favorites)
<br>
#1: create your first JS function helloWorld
<br>
#2: Basic data types--Number
<br>
#3: Basic data types--String
<br>
#4: Basic data types--Array
<br>
#5: Basic data types--Object
<br>
#6: Basic data types--Boolean and conditional statements if..else
<br>
#7: if..else and ternary operator
<br>
#8: Conditional statement--switch
<br>
#9: loop statement --while and do..while
<br>
#10: loop statement --for
<br>
#11: loop statement --break,continue
<br>
#12: loop statement --for..in and for..of
<br>
#13: Number object and its properties
<br>
#14: Methods of Number object--toString() and toLocaleString()
<br>
#15: Methods of Number object--toFixed(), toExponential() and toPrecision()
<br>
#16: Methods of String object--slice(), substring() and substr()
<br>
#17: Methods of String object--indexOf(), lastIndexOf() and search()
<br>
#18: Methods of String object--concat() split() and its good friend join()
<br>
#19: Methods of String object--toUpperCase() toLowerCase() and replace()
<br>
#20: Methods of String object--charAt() charCodeAt() and fromCharCode()
<br>
#21: Methods of String object--trim() and the string template
<br>
#22: Unlock new skills--Arrow function,spread operator and deconstruction
<br>
#23: methods of arrayObject---push(), pop(), shift() and unshift()
<br>
#24: methods of arrayObject---splice() and slice()
<br>
#25: methods of arrayObject---reverse() and sort()
<br>
#26: methods of arrayObject---map()
<br>
#27: methods of arrayObject---filter()
<br>
#28: methods of arrayObject---every() and some()
<br>
#29: methods of arrayObject---concat() and join()
<br>
#30: methods of arrayObject---reduce() and reduceRight()
<br>
#31: methods of arrayObject---isArray() indexOf() and toString()
<br>
#32: methods of Math---round() ceil() and floor()
<br>
#33: methods of Math---max() min() and abs()
<br>
#34: methods of Math---pow() sqrt() and cbrt()
<br>
#35: methods of Math---log() and its family
<br>
#36: methods of Math---kata author's lover:random()
<br>
#37: Unlock new weapon---RegExp Object
<br>
#38: Regular Expression--"^","$", "." and test()
<br>
#39: Regular Expression--"?", "*", "+" and "{}"
<br>
#40: Regular Expression--"|", "[]" and "()"
<br>
#41: Regular Expression--""
<br>
#42: Regular Expression--(?:), (?=) and (?!)
<br>
