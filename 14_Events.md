# Events
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.

When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

Developers can use these events to execute JavaScript coded responses, which cause buttons to close windows, messages to be displayed to users, data to be validated, and virtually any other type of response imaginable.

Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.

Please go through this small tutorial for a better understanding HTML Event Reference. Here we will see a few examples to understand a relation between Event and JavaScript −

## onclick Event Type
This is the most frequently used event type which occurs when a user clicks the left button of his mouse. You can put your validation, warning etc., against this event type.

### Example
Try the following example.

```html
<html>
   <head>   
      <script type = "text/javascript">
         <!--
            function sayHello() {
               alert("Hello World")
            }
         //-->
      </script>      
   </head>
   
   <body>
      <p>Click the following button and see result</p>      
      <form>
         <input type = "button" onclick = "sayHello()" value = "Say Hello" />
      </form>      
   </body>
</html>
```

## onsubmit Event Type
onsubmit is an event that occurs when you try to submit a form. You can put your form validation against this event type.

### Example
The following example shows how to use onsubmit. Here we are calling a validate() function before submitting a form data to the webserver. If validate() function returns true, the form will be submitted, otherwise it will not submit the data.

Try the following example.

```html
<html>
   <head>   
      <script type = "text/javascript">
         <!--
            function validation() {
               all validation goes here
               .........
               return either true or false
            }
         //-->
      </script>      
   </head>
   
   <body>   
      <form method = "POST" action = "t.cgi" onsubmit = "return validate()">
         .......
         <input type = "submit" value = "Submit" />
      </form>      
   </body>
</html>
```

## onmouseover and onmouseout
These two event types will help you create nice effects with images or even with text as well. The onmouseover event triggers when you bring your mouse over any element and the onmouseout triggers when you move your mouse out from that element. Try the following example.

```html
<html>
   <head>   
      <script type = "text/javascript">
         <!--
            function over() {
               document.write ("Mouse Over");
            }            
            function out() {
               document.write ("Mouse Out");
            }            
         //-->
      </script>      
   </head>
   
   <body>
      <p>Bring your mouse inside the division to see the result:</p>      
      <div onmouseover = "over()" onmouseout = "out()">
         <h2> This is inside the division </h2>
      </div>         
   </body>
</html>
