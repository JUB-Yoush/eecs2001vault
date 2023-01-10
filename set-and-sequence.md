#notation
#todo 
# set
- unoredered group of objects represented as a unit, they can contain numbers, words, or any kind of abstract element
- the order and repition do not matter
- S = {7,21,57} is a set containing 7,21 and 57
- the symbols $\in$ and $\not \in$ represent an element existing or not existing in a set
	- 7 $\in$ S is true 
	- 57 $\not \in$ set is false

### multiset
- sets usually ignore duplicates, however you can take the number of occurances of members into account by using a multiset instead of a set
- the set {7} and {7,7} are the same set but different multisets

### infinite set
- we can have sets that have infinte amounts of values by figuring out what kind of values should be in the set
	- a set of all the natural numbers 
	- a set of all intergers
	- a set of all the intergers multiplied by 3
- we can't write these sets out, so we represent them with ... in place of where the rest of the values would go 
	- {1,2,3,...}
	- {... -2,-1,0,1,2...}
	- {-6,-3,0,3,6}
- some common infinte sets have letters associated to represent them, you can find a list of them [here](https://www.rapidtables.com/math/symbols/Set_Symbols.html)

### subset
- Set A is a subset of Set B if every member of A is also a member of B
- this is represented by the $\subseteq$ symbol
- it could also be a proper subset, which means A is not equal to B (A is not a subset of B because they're the same set), represented by the $\subset$


### intersection
- an operation that returns the values that two sets share

### union
- an operation that joins the values of two sets together

### cross-product
- if A and B are two sets then the Cartesican product or cross-product of A and B (written as A$\times$B) is the set of all ordered pairs wherein the first element is a member of A and the second element is a member of B.
- imagine making a grid and the x axis was A and the y axis was B
	- if A = {1,2} and B = {x,y,z}
	- $A \times B$ = { (1, x), (1, y), (1, z), (2, x), (2, y), (2, z) }
	
### power-set
- the power set of A is the set of all subsets of A. If A is the set {0,1}, the pwoer if set of A is {0,1} the power set of A is a set of every subset of a, so it would be {{$\emptyset$},{0},{1},{0,1}}

# sequence
- a sequence is a ordered list of objects
- the values in the tuple are written in parentheses.
- (7,21,57) is a tuple
- unlike sets, duplicates and ordering matters
### tuple
- a finite sequence
- A sequence of k elements is called a **k-tuple**
- so (7,21,57) is a 3-tuple
- a 2-tuple is called an **ordered-pair**
