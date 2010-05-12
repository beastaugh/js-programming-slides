!SLIDE
# 3: Statements & Functions

!SLIDE smbullets incremental
# Statements

* `var` statements
* Conditionals (`if`)
* Loops (`while`, `do`, `for`, `for in`)
* Disruptive statements (`break`, `return`, `throw`)
* Expression statements

!SLIDE smbullets incremental
# Blocks

* Groups of statements
* Conditionals, loops and functions all accept blocks
* Blocks do not create new scopes

!SLIDE smbullets incremental
# Functions

* Functions are reusable blocks of statements (subroutines)
* Functions introduce a new scope
* Functions are objects
* Functions are "first-class" values

!SLIDE bullets incremental
# Invoking functions

* `()`
* `call` and `apply`
* `new`

!SLIDE smbullets incremental
# Introducing variables

* Local variables can be declared with `var`
* Or as function parameters

!SLIDE smbullets incremental
# Scope

* Defining a function creates a new scope
* Variables are local to a scope
* But are visible to functions defined within that scope (closures)
* JavaScript has a global object (`window` in browsers)
* Properties of the global object are visible in all scopes

!SLIDE smbullets incremental
# Primitives versus objects

* JavaScript values are either _primitives_ or _objects_
* The primitive types are booleans, strings, numbers, `undefined` and `null`
* Everything else is an object

!SLIDE bullets incremental
# Equality

* Primitives can be compared for _value equality_
* Objects must be compared for _object equality_

!SLIDE smbullets incremental
# Arguments

* Functions have _parameters_
* The actual values passed to the function are called _arguments_
* They can be referenced by name
* Or via the special `arguments` object
* (Which is not an array, but behaves a lot like one)
* Primitives are _passed by value_
* Objects are _passed by reference_
