# HTML-Input-saver
A little js script that saves user input using javascript cookies.


# HOW IT WORKS
The script finds all input (except type='submit') and textarea elements.It sets value change listener and 'onchange' it saves it's value into cookies.
<br>
Just add `<script type="text/javascript" src="YOUR_PATH/js/htmlInputSaver.js"></script>` at the end of `<body>` element and all text field will be autosaving values so user don't lose progress
<br>
**All input and textarea elements must have 'name' proprety** 
<br>`<input type="text" name="firstName" placeholder="Your name" required>`
