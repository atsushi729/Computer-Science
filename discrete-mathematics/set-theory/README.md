# Set
## What is Set?
In discrete mathematics, a set is a collection of distinct objects, called elements or members, that are considered as a single entity.<br>
Sets are an important concept in discrete mathematics because they allow us to define and manipulate the structure of collections of objects. <br>
Sets are typically denoted by enclosing the elements in curly braces, for example: {1, 2, 3, 4}. 
The order of the elements in a set is usually not important, so {1, 2, 3, 4} is considered to be the same set as {4, 3, 2, 1}.<br>
Some sets can be infinite, for example the set of all natural numbers (1, 2, 3, ...).<br>
Sets can be used to represent relationships between objects, for example, we can define a set of all the students in a class, or a set of all the countries in the world. Sets are a fundamental concept in mathematics and computer science, and they have many applications in various fields such as computer algorithms, data structures, and programming languages.

### Element of set (∈)
As mentioned above sentence, element is a member of a set. It is a specific object that belongs to a set.
For example, in the set {1, 2, 3, 4}, the elements are 1, 2, 3, and 4.
In Discrete mathematics, element can be denote as ∈. ∈ ---> Element

### Cardinality
Cardinality is the number of elements contained in Set.<br>
In Discrete mathematics, cardinality can be denoted as |S|.<br>
For example, if S = {1, 2, 3, 4, 5}, then cardinality of S is 5. In other words, |S| = 5.<br>
※note <br>
if S is empty, then cardinality is 0.<br>

### Subset
a subset is a collection of objects (elements) that are chosen from a larger set. <br>
For example, if we have a set A which contains the elements 1, 2, and 3, then the set {1, 2} is a subset of A. <br>
The symbol used to represent that a set is a subset of another set is ⊆. <br>
So, we can write {1, 2} ⊆ A to indicate that {1, 2} is a subset of A.<br>

※note<br>
Empty set is a subset of any set(∅ ⊆ S)<br>

### Powerset
Powerset is the set which containing all the subset of S, it can be denoted as P(S).
Example :
Given a set S = {1,2,3}<br>
the powerset is P(S) = {∅,{1},{2},{3},{1,2},{1,3},{2,3},{1,2,3}}<br>
thus powerset containing all subset of S.<br>

#### Cardinality of powerset
cardinality of powerset can be calculated by following formula:<br>
| P(S) | = 2^|S| <br>

Example : <br>
S={1,2,3}.    |S| = 3<br>
P(S) = {∅,{1},{2},{3},{1,2},{1,3},{2,3},{1,2,3}}<br>
| P(S) | = 8 = 23 = 2^|S|<br>


### Set operations
the union of two sets is a new set that contains all the elements from both of the original sets. 
Symbolically, if A and B are sets, then the union of A and B is denoted as A ∪ B and is defined as the set of all elements that belong to either A or B, or to both.
For example, if A = {1, 2, 3} and B = {2, 3, 4}, then A ∪ B = {1, 2, 3, 4}.