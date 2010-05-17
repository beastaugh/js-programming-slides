!SLIDE
# 4: Constructors & Prototypes

!SLIDE smbullets incremental
# Constructors

* Constructors make new objects
* Constructors are _functions_
* Constructors can be invoked with the `new` operator
* E.g. `new Date()`
* You can define your own constructors
* (They're just functions)

!SLIDE smbullets incremental
# Prototypes

* JavaScript's object system is _prototypal_
* Every object inherits from a prototype
* Prototypes are objects
* Every constructor has a `prototype` property
* Objects created by invoking that constructor are based on the prototype

!SLIDE smbullets incremental
# `instanceof`

* The `instanceof` operator states whether an object is an instance of that
  type
* So `({}) instanceof Object` evaluates to `true`
* `(function() {}) instanceof Function` evaluates to `true`
* And so does `(function() {}) instanceof Object`...
* ...because `Object` is in the prototype chain of the function
