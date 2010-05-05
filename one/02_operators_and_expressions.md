!SLIDE
# 2: Operators & Expressions

!SLIDE bullets incremental
# Classifying operators

* _Arity_ (number of operands)
* _Fixity_ (prefix, infix or postfix)
* _Kind_ (type of operation)

!SLIDE bullets incremental
# Operator arity

* Unary: `typeof foo`
* Binary: `bar instanceof baz`
* Ternary: `x ? y : z`

!SLIDE bullets incremental
# Operator fixity

* Prefix: `new Date`
* Infix:  `a % b`
* Postfix: `f++`

!SLIDE smbullets incremental
# Operator kinds

* Arithmetic operators
* Assignment operators
* Comparison operators
* Logical operators
* String operators
* Member operators
* Special operators

!SLIDE bullets incremental
# Operator gotchas

* `==` and `!=` perform _type coercion_
* Use `===` and `!==` for equality and inequality tests
* `&&` and `||` are short-circuit operators
* Short-circuit operations evaluate to the stopping expression

!SLIDE bullets incremental
# Expressions

* Expressions are defined _recursively_
* Expressions can be _values_
* Expressions can be _compositions_ of operators and other expressions

!SLIDE center

![JavaScript syntax diagram for expressions](expressions_syntax_diagram.png)

_Source: _JavaScript: The Good Parts _by Doug Crockford_
