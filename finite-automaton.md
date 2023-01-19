- the simplest computer you can make
- they have extremeley limited memory but can actaully be quite useful for common tasks
- Example: power button
	- ![[simple-dfa]]
	- if the power is off then turn it on
	- if the power is on then turn it off

more complicated computers have more components to them

### 5-tuple
- a formal definition of a DFA uses 5 sybmols listed in a [[tuple]], the symbols are:

| Symbol                   | Meaning                                           |
| ------------------------ | ------------------------------------------------- |
| $\mathbb{Q}$             | finite set of states                              |
| $\Sigma$                 | Finite set of the alphabet                        |
| $\delta$                 | $\mathbb{Q} \times \Sigma \rightarrow \mathbb{Q}$ |
| $q_0 \in \mathbb{Q}$     | the start state                                   |
| $F \subseteq \mathbb{Q}$ | set of accept states                              |                         |                                                   |
