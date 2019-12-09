---
layout: post
title:      "Ruby topics: Self"
date:       2019-12-09 03:37:33 +0000
permalink:  ruby_topics_self
---


Self in Ruby is a variable that refers to object ownership. When you use self, you are referring to the object that is directly responsible for the part of the code you are writing, or the "current" object when the code is run, no matter where you use it. It refers to one object at any given time, but changing where you use it can change which object that is.

If you use self inside an instance method, it refers to the instance. The code inside an instance method is "owned" by the instance.

If you use self inside a class method, it refers to the class. The code inside a class method is "owned" by the class.

If you use self inside a module's "class" method, it refers to the module. This works the same way as inside a class.

If you use self outside of any class, it refers to main, an instance of Object class.

Things can get complicated as you combine modules and classes, but in the end, it comes back to these basic concepts.


# Ruby topics: Return values
A method's return value is the value that is sent back to the code that called that method. The value can be any one object, but it is always something (even nil is an object). 

The last expression evaluated in a method automatically becomes its return value. Return value can otherwise be assigned with the "return" keyword.
