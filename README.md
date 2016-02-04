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
