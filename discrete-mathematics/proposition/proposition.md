# What is the "Propositional logic"
***
## Introduction (about Proposition)
--> A propositional statement is a declarative statement that is **either true or false, but not both.**

### Example
* Tokyo is the capital of Japan. → This is proposition(because statement is true)
* 1 + 2 = 4 → This is proposition(because statement is false)
* $x = y$ → This is **not** proposition(because there is no way to identify value of x).

## Propositional variable
To avoid writing long and repetitive propositions, we use proposition variable:<br>
A propositional variable is typically a letter, like **p, q, r**.

### Example
* p : Tokyo is the capital of Japan.
* q : 2 + 2 = 4
* r : 2 < 3

## Truth table
--> A truth table is a tabular representation of all the possible combination of its constituent variable.
※The number of rows in truth table for **n** proposition is 2^n

<table>
  <thead>
    <tr>
      <th>p</th>
      <th>q</th>
      <th>p ∧ q</th>
      <th>p ∨ q</th>
      <th>~(p ∧ q)</th>
      <th>~(p ∨ q)</th>
      <th>~p ∧ ~q</th>
      <th>~p ∨ ~q</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>T</td>
      <td>T</td>
      <td>T</td>
      <td>T</td>
      <td>F</td>
      <td>F</td>
      <td>F</td>
      <td>F</td>
    </tr>
    <tr>
      <td>T</td>
      <td>F</td>
      <td>F</td>
      <td>T</td>
      <td>T</td>
      <td>F</td>
      <td>F</td>
      <td>T</td>
    </tr>
    <tr>
      <td>F</td>
      <td>T</td>
      <td>F</td>
      <td>T</td>
      <td>T</td>
      <td>F</td>
      <td>F</td>
      <td>T</td>
    </tr>
    <tr>
      <td>F</td>
      <td>F</td>
      <td>F</td>
      <td>F</td>
      <td>T</td>
      <td>T</td>
      <td>T</td>
      <td>T</td>
    </tr>
  </tbody>
</table>


## Truth set
--> Let *p* be a proposition on a set *S*. The truth set of *p* is the set of elements of *S* for which *p* is true.<br>
We use capital letter to denote a truth set of a proposition.
**Propositon -> *p*,  Truth set -> *P*.**

### Example
Let S = {1,2,3,4,5,6,7,8,9,10}

Let *p and q* be two propositions concerning an integer n in *S*, defined as follows.
```angular2html
p: n is even
q: n is odd
```

 - The truth set of p written as P is :
***P* = {2,4,6,8,10}**

 - The truth set of p written as Q is :
***P* = {1,3,5,7,9}**









