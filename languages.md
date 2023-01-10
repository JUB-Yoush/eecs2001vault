- [[set|sets]] of [[string|Strings]] 
- for every string in each set, we say the string is in the language

## language-operations
- languages are sets and we can preform operations on them like any other set

### union
- add's two sets together, repeat values are ignored 
	Language A = {mango, orange}
	Language B = {green, orange}
	A $\cup$ B = {mango, orange, green}

### intersection
- checks which values are the same between two sets:
	Language A = {mango, orange}
	Language B = {green, orange}
	A $\cap$ B = {orange}


### concatenation
- when you concatenate a string A and B, it returns a new set of strings that start with a string in A and end in a string in B
	Language A = {mango, orange}
	Language B = {green, orange}
	A $\circ$  B = {mangogreen, mangoorange, orangegreen, orangeorange}
	doing B $\circ$ A would result in