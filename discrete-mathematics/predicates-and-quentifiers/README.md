# Predicates and quantifiers

## What is quantifiers?
We usually use some, all, every, none to count objects and this kind of words indicating quantity.Such words are called quantifiers.
There are two types of quantifier exists, universal quantifier and existential quantifier.

<br>

### Universal quantifier
This quantifier indicate for *all*, each, every, it is denoted by `∀`, an inverse of `A`.

*Example*
∀x P(x) asserts that P(x) is true for every x in the domain.

<br>

### Existential quantifier
This quantifier indicate for some, there exist, *at least*, it is denoted by `∃`, an inverse of `E`.

*Example*
∃x P(x) asserts that P(x) is true for some x in the domain.

<br>

### Uniqueness quantifier
This quantifier indicate that there exists a unique value x in the universe of discourse.
It is denoted by `∃!`

<br>

### Nested Quantifiers
To express complex statement with multiple variables we use nested quantifiers.

<br>

## Predicate
This is the states and domain x has in under some specific domain.
Predicate is just sign of condition.
We have condition like "All ball are green" then we can rewrite P(x).

<br>

### Binding variable
Variables in the scope of some quantifiers are called *bound* variables.
All other variables in the expression are called *free* variables.<br>

*Example*<br>
∃x P(x, y)<br>
* x -> bound<br>
* y -> free<br>

<br>

### Precedence of Quantifiers
Quantifiers ∀ and ∃ have higher precedence then all logical operators.

∀x P(x)∧Q(x) means (∀x P(x))∧Q(x). In particular, this expression contains a free variable.

#What is Recursive?
recursion refers to the process of defining a function or sequence in terms of itself. This is often done by defining a base case and a recursive case, where the function or sequence is defined in terms of itself for input values greater than the base case, and the base case is used for input values equal to or less than the base case. For example, the Fibonacci sequence is defined recursively, where the nth number in the sequence is the sum of the (n-1)th and (n-2)th numbers in the sequence.