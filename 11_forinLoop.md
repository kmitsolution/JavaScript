# for...in loop

The for...in loop is used to loop through an object's properties. As we have not discussed Objects yet, you may not feel comfortable with this loop. But once you understand how objects behave in JavaScript, you will find this loop very useful.

## Syntax
The syntax of ‘for..in’ loop is −

```
for (variablename in object) {
   statement or block to execute
}
```

In each iteration, one property from object is assigned to variablename and this loop continues till all the properties of the object are exhausted.

### Example
Try the following example to implement ‘for-in’ loop. It prints the web browser’s Navigator object.

```html
<html>
   <body>      
      <script type = "text/javascript">
         <!--
            var aProperty;
            document.write("Navigator Object Properties<br /> ");        
            for (aProperty in navigator) {
               document.write(aProperty);
               document.write("<br />");
            }
            document.write ("Exiting from the loop!");
         //-->
      </script>      
      <p>Set the variable to different object and then try...</p>
   </body>
</html>
```

### Output
```
Navigator Object Properties 
serviceWorker 
webkitPersistentStorage 
webkitTemporaryStorage 
geolocation 
doNotTrack 
onLine 
languages 
language 
userAgent 
product 
platform 
appVersion 
appName 
appCodeName 
hardwareConcurrency 
maxTouchPoints 
vendorSub 
vendor 
productSub 
cookieEnabled 
mimeTypes 
plugins 
javaEnabled 
getStorageUpdates 
getGamepads 
webkitGetUserMedia 
vibrate 
getBattery 
sendBeacon 
registerProtocolHandler 
unregisterProtocolHandler 
Exiting from the loop!
Set the variable to different object and then try...
