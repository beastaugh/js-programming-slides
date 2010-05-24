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
* But in practice, all JS interpreters use _insertion order_
* Property names can be strings or numbers
* But keys are converted to strings
* Some things that are syntax errors when using object literals become legal
  (if confusing) when using square bracket notation

!SLIDE smbullets incremental
# `hasOwnProperty`

* Use: `object.hasOwnProperty(someName)`
* Does a property belong to an object?
* Or is it just borrowed from somewhere else?
* I.e. further up the prototype chain
