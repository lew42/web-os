# Code is part of the problem

TL;DR

* Writing code is the way of the past
* Using a UI to create programs is the way of the future
* Syntax becomes a non-point; designers can redesign the interface as much as they want
* This allows granular version control

This doesn't have to appear any different than how it currently works.  If you want your IDE to feel like Sublime Text, or whatever, that's fine.  You can still poke away at your keyboard, typing the syntax, and auto completing.

But instead of 

After all, auto-complete *is* the interface I'm referring to, but only partially.  We can auto-complete a variable name, no problem.  But the program doesn't remember that you've "chosen" this variable.  And when you 

When you store, and version control code via the AST, you enable a world of possibilities

* Let the IDE manage all variable names.  Believe it or not, namespace issues 

* Code is often parsed into an abstract syntax tree (AST), which is basically the "parsed" version of the code.  This is way more useful.

Consider the following workflow:

1.  Create code (the AST) with a user interface
2.  The AST can be exported to actual code
3.  This can happen at runtime, so 

When you consider the evolution of a language (say, JavaScript), you're talking about syntax.  You need to be backwards compatible, and so you can't make breaking changes.

Code is syntax.  
