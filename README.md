## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.
Scope is for when you have variables defined in different areas of the code.  Some
may be defined locally within a function, and can only be accessed within that function
while some are defined globally can can be accessed at any time.  Hoisting has to do with
the way some browsers will "hoist" variables and functions to a different position to make
it work.  It is not something to rely on.  Compartmentalization is the concept of keeping
your functions and variables in with one single function, or group of functions.

### Provide examples for all three, below:

#### Scope:
var a = "shoes" can be defined either globally, outside a function, or locally
inside a function.

#### Hoisting:
Hoisting is when javascript moves variables to the top of the function that they
are contained in.  This is a little sketchy though, you should use best practices
for your variables to begin with.


#### Compartmentalization:
This is combining functions and variables to be contained in the code where they are
working.  You have to be careful with global and local variables.
