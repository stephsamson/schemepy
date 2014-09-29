schemepy
========

A toy Scheme interpreter written in Python. With guidance from Peter Norvig's
[lispy tutorial](http://norvig.com/lispy.html) and Mary Rose Cook's
[Little Lisp Interpreter](https://www.hackerschool.com/blog/21-little-lisp-interpreter).

to use
--------
* download, clone, or fork
* navigate to directory
* run `python scheme.py` or `rlwrap python scheme.py` if you have rlwrap installed for readline support.


what it does
--------
It evaluates:
* `if` statements
* `let` and `lambda` expressions
* some simple math
 
it can also `define` a variable and evaluate its expression if it has any.

what it doesn't do
--------
`set!`, `begin`

todo
--------
* Implement the stuff in the what it doesn't do section
* Definitely refactor
* Write better tests

special thanks
--------
* [Connor Osborn](https://github.com/cdosborn)
* [Zach Allaun](https://github.com/zachallaun)
* [Jesse Luehrs](https://github.com/doy)
* [Tom Ballinger](https://github.com/thomasballinger)


Made with lots of tears and ![heart](http://i.imgur.com/kYH7kJV.gif) at [Hacker School](http://hackerschool.com).
