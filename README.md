# XSS-keylogger

A keylogging script that can be injected into websites vulnerable to cross-site scripting.

The script tracks user keypresses by concatenating each keypress into a string that is POSTed to a server.

The script can be found in file keylogscript.html and can be tested on file captainslog.html.
The POST request is currently commented out, but if you wanted to use it, just uncomment and provide the URL that you want the data to be sent to.

captainslog.html was an assignment completed for my web programming class, and is one of many XSS-vulnerable pages that I've made. Simply paste the script (without newlines) into the textbox and submit. On other vulnerable websites, scripts may need to be a body parameter sent via POST. 

This can also manually be added to the source code of websites through developer console. Simply open up a webpage, pop open the element inspector and paste the script into the HTML. Then close the inspector and let your target do their thing. Note that this is untested.

Not responsible any mayhem that ensues, nor am I endorsing any black-hat activity.