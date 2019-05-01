# ES6toES5Plugin for Sublime text
This is a plugin for sublime text written in python for converting ES6 to ES5 using babel.

1.	Setup babel - https://babeljs.io/setup.html#installation locally.
2.	Sublime text3 > Tools > Developer > New Plugin ..
3.	Point new plugin to the python file enclosed in the mail.
4.	Update the location of babel – 
view.window().run_command('exec',{'cmd': [<location of babel.cmd in filesystem>, es6File, "-o", filename+".js"] }).
  
You can add as many Babel option in the the babel command as per your requirement.


