!SLIDE
# 6: Handling objects

!SLIDE smbullets incremental
# Dots and brackets

* You can use dot notation to access a property
* E.g. `foo.bar`
* But only when the property name is a valid identifier
* Otherwise you have to use square bracket notation
* E.g. `foo['bar']`

!SLIDE smbullets incremental
# Enumerating properties

* Enumerate the properties of an object with `for...in`
* The specification _doesn't_ guarantee order
* But in practice, all JS interpreters use _definition order_
* Property names can be strings or numbers
* But keys are converted to strings
* Some things that are syntax errors when using object literals become legal
  (if confusing) when using square bracket notation

!SLIDE smbullets incremental
# `hasOwnProperty`

* `object.hasOwnProperty(someName)`
* Does the property belong to an object?
* Or is it just borrowed from somewhere else?
* I.e. further up the prototype chain

!SLIDE smbullets incremental
# `delete`

* Remove properties from objects with the `delete` operator
* E.g. `delete foo.bar` on an object
* `delete foo['bar']` works too
* Or `delete foo[0]` on an array
* Doesn't work on variables!

!SLIDE smbullets incremental
# Deleting inherited properties

* Properties inherited from a prototype can't be deleted
* `delete` always evaluates to `true`...
* ...unless a property can't be deleted
* In which case it evaluates to `false`
* The property can be deleted directly from the prototype
