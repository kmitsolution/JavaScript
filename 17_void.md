# void
void is an important keyword in JavaScript which can be used as a unary operator that appears before its single operand, which may be of any type. This operator specifies an expression to be evaluated without returning a value.

### Syntax
The syntax of void can be either of the following two −

```html
<head>
   <script type = "text/javascript">
      <!--
         void func()
         javascript:void func()
         or:
         void(func())
         javascript:void(func())
      //-->
   </script>
</head>
```

### Example 1
The most common use of this operator is in a client-side javascript: URL, where it allows you to evaluate an expression for its side-effects without the browser displaying the value of the evaluated expression.

Here the expression alert ('Warning!!!') is evaluated but it is not loaded back into the current document −

```html
<html>
   <head>      
      <script type = "text/javascript">
         <!--
         //-->
      </script>   
   </head>
   
   <body>   
      <p>Click the following, This won't react at all...</p>
      <a href = "javascript:void(alert('Warning!!!'))">Click me!</a>     
   </body>
</html>

```

## Example 2 
Take a look at the following example. The following link does nothing because the expression "0" has no effect in JavaScript. Here the expression "0" is evaluated, but it is not loaded back into the current document.

```html
<html>
   <head>   
      <script type = "text/javascript">
         <!--
         //-->
      </script>      
   </head>
   
   <body>   
      <p>Click the following, This won't react at all...</p>
      <a href = "javascript:void(0)">Click me!</a>      
   </body>
</html>
```
