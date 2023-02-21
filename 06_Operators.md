
<h2>What is an Operator?</h2> 
<p>Let us take a simple expression <b>4 + 5 is equal to 9</b>. Here 4 and 5 are called <b>operands</b> and ‘+’ is called the <b>operator</b>. JavaScript supports the following types of operators.</p>
<ul class="list">
<li>Arithmetic Operators</li>
<li>Comparison Operators</li>
<li>Logical (or Relational) Operators</li>
<li>Assignment Operators</li>
<li>Conditional (or ternary) Operators</li>
</ul>
<p>Lets have a look on all operators one by one.</p>
<h2>Arithmetic Operators</h2>
<p>JavaScript supports the following arithmetic operators &minus;</p>
<p>Assume variable A holds 10 and variable B holds 20, then &minus;</p>
<table class="table table-bordered">
<tr>
<th style="text-align:center;width:9%;">Sr.No.</th>
<th style="text-align:center;">Operator &amp; Description</th>
</tr>
<tr>
<td class="ts">1</td>
<td><p><b>+ (Addition)</b></p>
<p>Adds two operands</p>
<p><b>Ex:</b> A + B will give 30</p>
</td>
</tr>
<tr>
<td class="ts">2</td>
<td><p><b>- (Subtraction)</b></p>
<p>Subtracts the second operand from the first</p>
<p><b>Ex:</b> A - B will give -10</p>
</td>
</tr>
<tr>
<td class="ts">3</td>
<td><p><b>* (Multiplication)</b></p>
<p>Multiply both operands</p>
<p><b>Ex:</b> A * B will give 200</p>
</td>
</tr>
<tr>
<td class="ts">4</td>
<td><p><b>/ (Division)</b></p>
<p>Divide the numerator by the denominator</p>
<p><b>Ex:</b> B / A will give 2</p>
</td>
</tr>
<tr>
<td class="ts">5</td>
<td><p><b>% (Modulus)</b></p>
<p>Outputs the remainder of an integer division</p>
<p><b>Ex:</b> B % A will give 0</p>
</td>
</tr>
<tr>
<td class="ts">6</td>
<td><p><b>++ (Increment)</b></p>
<p>Increases an integer value by one</p>
<p><b>Ex:</b> A++ will give 11</p>
</td>
</tr>
<tr>
<td class="ts">7</td>
<td><p><b>-- (Decrement)</b></p>
<p>Decreases an integer value by one</p>
<p><b>Ex:</b> A-- will give 9</p>
</td>
</tr>
</table>
<p><b>Note</b> &minus; Addition operator (+) works for Numeric as well as Strings. e.g. "a" + 10 will give "a10".</p>
<h3>Example</h3>
<p>The following code shows how to use arithmetic operators in JavaScript.</p>
<div class="demo-view">

</div>
<pre class="prettyprint notranslate">
<html>
   <body>
   
      <script type = "text/javascript">`
         <!--
            var a = 33;
            var b = 10;
            var c = "Test";
            var linebreak = "<br />";
         
            document.write("a + b = ");
            result = a + b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a - b = ");
            result = a - b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a / b = ");
            result = a / b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a % b = ");
            result = a % b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a + b + c = ");
            result = a + b + c;
            document.write(result);
            document.write(linebreak);
         
            a = ++a;
            document.write("++a = ");
            result = ++a;
            document.write(result);
            document.write(linebreak);
         
            b = --b;
            document.write("--b = ");
            result = --b;
            document.write(result);
            document.write(linebreak);
         //-->
      </script>
      
      Set the variables to different values and then try...
   </body>
</html>
</pre>
<h3>Output</h3>
<pre class="result notranslate">
a + b = 43
a - b = 23
a / b = 3.3
a % b = 3
a + b + c = 43Test
++a = 35
--b = 8
Set the variables to different values and then try...
</pre>
<h2>Comparison Operators</h2>
<p>JavaScript supports the following comparison operators &minus;</p>
<p>Assume variable A holds 10 and variable B holds 20, then &minus;</p>
<table class="table table-bordered">
<tr>
<th style="text-align:center;">Sr.No.</th>
<th style="text-align:center;">Operator &amp; Description</th>
</tr>
<tr>
<td class="ts">1</td>
<td>
<p><b>= = (Equal)</b></p>
<p>Checks if the value of two operands are equal or not, if yes, then the condition becomes true.</p>
<p><b>Ex:</b> (A == B) is not true.</p>
</td>
</tr>
<tr>
<td class="ts">2</td>
<td>
<p><b>!= (Not Equal)</b></p>
<p>Checks if the value of two operands are equal or not, if the values are not equal, then the condition becomes true.</p>
<p><b>Ex:</b> (A != B) is true.</p>
</td>
</tr>
<tr>
<td class="ts">3</td>
<td>
<p><b>> (Greater than)</b></p>
<p>Checks if the value of the left operand is greater than the value of the right operand, if yes, then the condition becomes true.</p>
<p><b>Ex:</b> (A > B) is not true.</p>
</td>
</tr>
<tr>
<td class="ts">4</td>
<td>
<p><b>< (Less than)</b></p>
<p>Checks if the value of the left operand is less than the value of the right operand, if yes, then the condition becomes true.</p>
<p><b>Ex:</b> (A < B) is true.</p>
</td>
</tr>
<tr>
<td class="ts">5</td>
<td>
<p><b>>= (Greater than or Equal to)</b></p>
<p>Checks if the value of the left operand is greater than or equal to the value of the right operand, if yes, then the condition becomes true.</p>
<p><b>Ex:</b> (A >= B) is not true.</p>
</td>
</tr>
<tr>
<td class="ts">6</td>
<td>
<p><b><= (Less than or Equal to)</b></p>
<p>Checks if the value of the left operand is less than or equal to the value of the right operand, if yes, then the condition becomes true.</p>
<p><b>Ex:</b> (A <= B) is true.</p>
</td>
</tr>
</table>

<h2>Bitwise Operators</h2>
<p>JavaScript supports the following bitwise operators &minus;</p>
<p>Assume variable A holds 2 and variable B holds 3, then &minus;</p>
<table class="table table-bordered">
<tr>
<th style="text-align:center;">Sr.No.</th>
<th style="text-align:center;">Operator &amp; Description</th>
</tr>
<tr>
<td class="ts">1</td>
<td><p><b>&amp; (Bitwise AND)</b></p>
<p>It performs a Boolean AND operation on each bit of its integer arguments.</p>
<p><b>Ex:</b> (A & B) is 2.</p>
</td>
</tr>
<tr>
<td class="ts">2</td>
<td><p><b>| (BitWise OR)</b></p>
<p>It performs a Boolean OR operation on each bit of its integer arguments.</p>
<p><b>Ex:</b> (A | B) is 3.</p>
</td>
</tr>
<tr>
<td class="ts">3</td>
<td><p><b>^ (Bitwise XOR)</b></p>
<p>It performs a Boolean exclusive OR operation on each bit of its integer arguments. Exclusive OR means that either operand one is true or operand two is true, but not both.</p>
<p><b>Ex:</b> (A ^ B) is 1.</p>
</td>
</tr>
<tr>
<td class="ts">4</td>
<td><p><b>~ (Bitwise Not)</b></p>
<p>It is a unary operator and operates by reversing all the bits in the operand.</p>
<p><b>Ex:</b> (~B) is -4.</p>
</td>
</tr>
<tr>
<td class="ts">5</td>
<td><p><b><< (Left Shift)</b></p>
<p>It moves all the bits in its first operand to the left by the number of places specified in the second operand. New bits are filled with zeros. Shifting a value left by one position is equivalent to multiplying it by 2, shifting two positions is equivalent to multiplying by 4, and so on.</p>
<p><b>Ex:</b> (A << 1) is 4.</p>
</td>
</tr>
<tr>
<td class="ts">6</td>
<td><p><b>>> (Right Shift)</b></p>
<p>Binary Right Shift Operator. The left operand’s value is moved right by the number of bits specified by the right operand.</p>
<p><b>Ex:</b> (A >> 1) is 1.</p>
</td>
</tr>
<tr>
<td class="ts">7</td>
<td><p><b>>>> (Right shift with Zero)</b></p>
<p>This operator is just like the >> operator, except that the bits shifted in on the left are always zero.</p>
<p><b>Ex:</b> (A >>> 1) is 1.</p>
</td>
</tr>
</table>

<h2>Assignment Operators</h2>
<p>JavaScript supports the following assignment operators &minus;</p>
<table class="table table-bordered">
<tr>
<th style="text-align:center;">Sr.No.</th>
<th style="text-align:center;">Operator &amp; Description</th>
</tr>
<tr>
<td class="ts">1</td>
<td><p><b>= (Simple Assignment )</b></p>
<p>Assigns values from the right side operand to the left side operand</p>
<p><b>Ex:</b> C = A + B will assign the value of A + B into C</p>
</td>
</tr>
<tr>
<td class="ts">2</td>
<td><p><b>+= (Add and Assignment)</b></p>
<p>It adds the right operand to the left operand and assigns the result to the left operand.</p>
<p><b>Ex:</b> C += A is equivalent to C = C + A</p>
</td>
</tr>
<tr>
<td class="ts">3</td>
<td><p><b>&minus;= (Subtract and Assignment)</b></p>
<p>It subtracts the right operand from the left operand and assigns the result to the left operand.</p>
<p><b>Ex:</b> C -= A is equivalent to C = C - A</p>
</td>
</tr>
<tr>
<td class="ts">4</td>
<td><p><b>*= (Multiply and Assignment)</b></p>
<p>It multiplies the right operand with the left operand and assigns the result to the left operand.</p>
<p><b>Ex:</b> C *= A is equivalent to C = C * A</p>
</td>
</tr>
<tr>
<td class="ts">5</td>
<td><p><b>/= (Divide and Assignment)</b></p>
<p>It divides the left operand with the right operand and assigns the result to the left operand.</p>
<p><b>Ex:</b> C /= A is equivalent to C = C / A</p>
</td>
</tr>
<tr>
<td class="ts">6</td>
<td><p><b>%= (Modules and Assignment)</b></p>
<p>It takes modulus using two operands and assigns the result to the left operand.</p>
<p><b>Ex:</b> C %= A is equivalent to C = C % A</p>
</td>
</tr>
</table>
<p><b>Note</b> &minus; Same logic applies to Bitwise operators so they will become like <<=, >>=, >>=, &amp;=, |= and ^=.</p>
<h3>Example</h3>
<p>Try the following code to implement assignment operator in JavaScript.</p>
<div class="demo-view">
<a href="http://tpcg.io/tmlXco" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> </a>
</div>

<h2>Miscellaneous Operator</h2>
<p>We will discuss two operators here that are quite useful in JavaScript: the <b>conditional operator</b> (? :) and the <b>typeof operator</b>.</p>
<h3>Conditional Operator (? :)</h3>
<p>The conditional operator first evaluates an expression for a true or false value and then executes one of the two given statements depending upon the result of the evaluation.</p>
<table class="table table-bordered">
<tr>
<th style="text-align:center;" width="10%">Sr.No.</th>
<th style="text-align:center;">Operator and Description</th>
</tr>
<tr>
<td class="ts">1</td>
<td><p><b>? : (Conditional )</b></p>
<p>If Condition is true? Then value X : Otherwise value Y</p>
</td>
</tr>
</table>
<h3>Example</h3>
<p>Try the following code to understand how the Conditional Operator works in JavaScript.</p>

```html
<html>
   <body>   
      <script type = "text/javascript">
         <!--
            var a = 10;
            var b = 20;
            var linebreak = "<br />";
         
            document.write ("((a > b) ? 100 : 200) => ");
            result = (a > b) ? 100 : 200;
            document.write(result);
            document.write(linebreak);
         
            document.write ("((a < b) ? 100 : 200) => ");
            result = (a < b) ? 100 : 200;
            document.write(result);
            document.write(linebreak);
         //-->
      </script>      
      <p>Set the variables to different values and different operators and then try...</p>
   </body>
</html>
</pre>
```

<h3>Output</h3>
<pre class="result notranslate">
((a > b) ? 100 : 200) => 200 
((a < b) ? 100 : 200) => 100
Set the variables to different values and different operators and then try...
</pre>
<h2>typeof Operator</h2>
<p>The <b>typeof</b> operator is a unary operator that is placed before its single operand, which can be of any type. Its value is a string indicating the data type of the operand.</p>
<p>The <i>typeof</i> operator evaluates to "number", "string", or "boolean" if its operand is a number, string, or boolean value and returns true or false based on the evaluation.</p>
<p>Here is a list of the return values for the <b>typeof</b> Operator.</p>
<table class="table table-bordered" style="text-align:center;">
<tr>
<th style="text-align:center;" width="20%">Type</th>
<th style="text-align:center;">String Returned by typeof</th>
</tr>
<tr>
<td>Number</td>
<td>"number"</td>
</tr>
<tr>
<td>String</td>
<td>"string"</td>
</tr>
<tr>
<td>Boolean</td>
<td>"boolean"</td>
</tr>
<tr>
<td>Object</td>
<td>"object"</td>
</tr>
<tr>
<td>Function</td>
<td>"function"</td>
</tr>
<tr>
<td>Undefined</td>
<td>"undefined"</td>
</tr>
<tr>
<td>Null</td>
<td>"object"</td>
</tr>
</table>
<h3>Example</h3>
<p>The following code shows how to implement <b>typeof</b> operator.</p>

```html
<html>
   <body>      
      <script type = "text/javascript">
         <!--
            var a = 10;
            var b = "String";
            var linebreak = "<br />";
         
            result = (typeof b == "string" ? "B is String" : "B is Numeric");
            document.write("Result => ");
            document.write(result);
            document.write(linebreak);
         
            result = (typeof a == "string" ? "A is String" : "A is Numeric");
            document.write("Result => ");
            document.write(result);
            document.write(linebreak);
         //-->
      </script>      
      <p>Set the variables to different values and different operators and then try...</p>
   </body>
</html>
```
<h3>Output</h3>
<pre class="result notranslate">
Result => B is String 
Result => A is Numeric
Set the variables to different values and different operators and then try...
</pre>
