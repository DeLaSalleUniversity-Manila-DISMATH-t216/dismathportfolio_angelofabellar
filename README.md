# dismathportfolio
by: Cris Angelo M.Fabellar

# DISMATH WEEK 1
(from dismathportfolio)


- This week I learned of a subject that is called Discrete mathematics. It tackles topics that are of low-level, meaning it is close to language of machines, rather than human thinking.
- I learned that proof or mathematical proof of a proposition is a chain of logical deductions leading to the proposition from a base set of axioms.
- A proposition is  a statement that is either true(1), or false(0).
- I learned that a proposition must not be a paradox. (eg. "This statement is false.")
- Logical deduction is a process of reasoning from one or more statements (premises) to reach a logically certain conclusion.
- An axiom is  a statement or a proposition that is regarded as being established, accepted, or self-evidently true. (eg. "a+c=b+c; a=b and b=a).


# DISMATH WEEK 2
(from dismathportfolio)


- I learned of the different logical connectives.
- A truth table is a table that lists all possible logical inputs with their corresponding outputs.
- I learned the symbols in logical connectives and the way how to prove it using the truth table.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- I learned that the Truth Table for Biconditional  is just the negation of Exclusive OR (XOR).

TRUTH TABLE FOR BICONDITIONAL

| p | q | p ↔ q |
| :---: | :---: | :---: |
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

TRUTH TABLE FOR NEGATION OF EXCLUSIVE OR

| p | q | p ⊕ q | ¬ ( p ⊕ q )|
| :---: | :---: | :---: | :---: | 
| 0 | 0 | 0 | 1 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

- I learned how to use Logical Equivalences in proving a certain expression, and its step-by-step procedure.


# DISMATH WEEK 3
(from dismathportfolio)


- Predicate Logic-concerned not only with logic relations between sentences or propositions as wholes, but the internal structure in terms of subject and predicate.
- ex. x>12, 'x' is the subject and 'is greater than 12' is the predicate.
- Quantifiers indicate the generality of open sentence in which a variable occurs
- Existential Quantifier (∃x), "there exists":P(x1)vP(x2)vP(x3)...vP(xn)
- one example that is true will gain a true value
- Universal Quantifier (∀x), "for all": P(x1)∧P(x2)∧P(x3)...∧P(xn)
- one example that is false will gain a false value
- We learned about Rules of inference


# DISMATH WEEK 4
(from dismathportfolio)

- We applied the rules of inference to different 
- We discussed proving, and the different methods of proving.
- We learned about direct proof, where you first assume the first statement true, and show the second statement to be true based on the first one.
- We learned about proof by Contraposition, or indirect proof, which assumes the second statement false, and shows the first ione toi be true based on the second statement.
- The next two are proof by Vacuous and Trivial. These two are easy to remember because they are patterned in the logical connective p → q. When p is F, p → q is automatically T (Vacuous), and when q is T, p → q is automatically T (Trivial).


# DISMATH WEEK 5
(from dismathportfolio)

- We learned about proof of Contradiction, where you will use the whole premise and the negation of that premise will show a contradiction of the statement.
- We also studied Mathematical Induction, which has a Basis Step, and then an Inductive Step using the Direct proof.
- For program correctness, we need an initial assertion, final assertion and a segment.

# DISMATH WEEK 6
(from dismathportfolio)
- We had an introduction to Set Theory, and it somewhat refreshed our learnings from our highschool mathematics.
- We discussed the definitions of set, empty set, membership, set-builder notations, and venn diagrams.
- We had also distinguished the properties of union, intersection, subtraction, and symmetric difference.
- The Set Identities have very similar inputs with the Logical Equivalences properties.
- Subsets and power sets were also discussed thoroughly.
- a subset can be a set of itself.
- example: the set {1,2,3,4} is a subset of {1,2,3,4} 
- The Power Series also has similar notations with the Geometric Series.

# DISMATH WEEK 7
(from dismathportfolio)
- We assign exactly one element to set B to say that it is a function.
- If it is not, it is called a relation
- The domain, co-domain and range were discussed with proper distinctions.
- There three types of functions: one-to-one function, onto function, and one-to-one correspondence.
- One-to-one function (injective) is a function that never assign the same value to two different domain elements.
- Onto function (surjective) is a function that have equal range and codomain.
- One-to-one correspondence (bijective) is the mixture of injective and surjective functions.
- In a venn diagram, the intersection of an injective function and surjective function is a bijective function.
- The box in which the Venn diagram lies is neither surjective, bijective or injective.

# DISMATH WEEK 7
(from dismathportfolio)
- An Algorithm is a finite set of precise instructions for performing a computation or for solving a problem.
- I learned that Pseudocode is the high-level description of an algorithm that uses the structural conventions (Input, Body, and Output)
- Properties of a correct Pseudocode are:Input, Output, Defineteness(if it is defined precisely), Correctness (if the output value is correct), Finiteness (it is limited with the given input), and Generality.
- Precondition describes a valid input 
- Postcondition is the output that was satisfied when the program run.

# DISMATH WEEK 8
(from dismathportfolio)
- **Searching Algorithms** - the problem of locating an element in an ordered list.
  - *Linear Search* -  finding a particular value in a list that checks each element in sequence until the desired element is found.
  - *Binary Search* - comparing the middle values of a list then repeated until the desired output is found.
- **Sorting Algorithms** - the problem of assorting elements into increasing order.
  - *Bubble Sort* - compares the first two elements then interchanging them if they are in the incorrect order.
  - *Insertion Sort* - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it     is inserted after the first element.
- **Greedy Algorithms** - algorithms that make what seems to be the "best" choice at each step. Selects the best choice at each step, instead of considering all sequences of steps that may lead to optimal solution.
 

# DISMATH WEEK 9
(from dismathportfolio)
- We started discussing Growth of Functions
- In the Growth of Function, it has a constants of C and k that describes as the witnesses.
- Big-O notation is the upper bound of a function.
- Big-Omega is the lower bound of a function, while Big-Theta is the upper and lower bound of a function.
- Mathematical definition:
  - Big-O: |f(x)| ≤ |C(g(x))|
  - Big-Omega: |f(x)| ≥ |C(g(x))|
  - Big-Theta: |C1(g(x))| ≤ |f(x)| ≤ |C2(g(x))|


# DISMATH WEEK 10
(from dismathportfolio)
- Time complexity was discussed and it's really hard to understand.
- It can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
		
  | Complexity | Terminology |
  | :---: | :---: |
  | ϴ(1) | constant complexity |
  | ϴ(log n) | log complexity |
  | ϴ(n) | linear complexity |
  | ϴ(n log n) | n log n complexity |
  | ϴ(n^b) | polynomial complexity |
  | ϴ(b^n) | exponential complexity |
  | ϴ(n!) | factorial complexity |

- Time complexity is dependent on the number of comparisons an algorithm have.
- Getting the time complexity is confusing so Sir used an iteration table to be able to explain how to get the number of comparisons.

# DISMATH WEEK 10
(from dismathportfolio)
- We learned about Euler Paths and circuits
- Euler path is a path that covers all edges
- Euler circuit covers all edges and goes from the starting vertex back to the original vertex along the way.
- Hamiltonian circuits and paths cover all nodes or vertices and goes from the starting node bak to the original.
- Hamiltonian path covers all nodes.
- 

