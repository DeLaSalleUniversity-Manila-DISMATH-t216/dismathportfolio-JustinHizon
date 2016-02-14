# dismathportfolio-JustinHizon
dismathportfolio-JustinHizon created by Classroom for GitHub
## Week 1:
- We were introduced by our professor and he gave us a general idea of what DISMATH is about.
- We learned about arguments and what is a propsition.
- I've learned the usage, as well as its formulas/logical expressions, of the following logical symbols:

 Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
 :-----: |:-------:|:-----:| :-------: | :-------: |
 ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
 ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
 v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
 ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
 → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
 ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |
- I knew how to verify a statement by using a Truth Table.
- Also, I've learned the different propositional logic such as:
  - Inverse of p → q: ¬p → ¬q
  - Converse of p → q: q → p
  - Contrapositive of p → q: ¬q → ¬p (which also happens to be the equivalent value of the original statement)

## Week 2:
- **Terminologies** (from Chapter 1.3)
  - A **tautology** is a compound proposition that is always true, no matter what the truth values of the propositional variables that occur in it. 
  - A **contradiction** is a compound proposition that is always false. 
  - A **contingency** is a compound proposition that is neither a tautology nor a contradiction.
- If Algebra has a variety of laws and rules in solving mathematical equations, Discrete Mathematics has its own set of laws and rules too. These are called **logical equivalences**. These are as follows:

|                           Equivalence                           |         Name        |
|:-------------------------------------------------------------:  |:-------------------:|
|                      p ∧ T ≡ p <br> p v F ≡ p                   |    Identity laws    |
|                       p v T ≡ T <br> p ∧ F ≡ F                  |   Domination laws   |
|                       p v p ≡ p <br> p ∧ p ≡ p                  |   Idempotent laws   |
|                            ¬(¬p) ≡ p                            | Double negation law |
|                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p              |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)  |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q          |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p             |   Absorption laws   |
|                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                   |    Negation laws    |

- We were introduced to a new topic: **Quantifiers**. The two types of quantification are the following:
  - *Universal Quantification* (∀) - "tells us that a predicate is true for every element under consideration"
    - To disprove this statement, one can use a counterexample.
  - *Existential Quantification* (∃) - "tells us that there is one or more element under consideration for which the predicate is true"

## Week 3:
- During this week, I was introduced to a topic called **Rules of Inference**.
- I was tought about arguments and to see if they are valid or a fallacy

### RULES OF INFERENCE TABLE   

|  **TYPE**  |  **RULE OF INFERENCE**  |  **TAUTOLOGY**  |
| -------: | :--------------: | :--------- |
|  _Modus Ponens_  |  p, p → q ∴ q  |  (p ∧ (p → q)) → q  |
|  _Modus Tollens_  |  ¬q, p → q ∴ ¬p |  (¬q ∧ (p → q)) → ¬p  |
|  _Hypothetical Syllogism_  |  p → q, q → r ∴ p → r  |  ((p → q) ∧ (q → r)) → (p → r)  |
|  _Disjunctive Syllogism_  |  p ∨ q, ¬p ∴ q  |  ((p ∨ q) ∧ ¬p) → q  |
|  _Addition_  |  p ∴ p ∨ q  |  p → p ∨ q  |
|  _Simplification_  |  p ∧ q ∴ p  |  (p ∧ q) → p  |
|  _Conjunction_  |  p, q ∴ p ∧ q  |  ((p) ∧ (q)) → (p ∧ q)  |
|  _Resolution_  |  p ∨ q, ¬p ∨ r ∴ q ∨ r  |  ((p ∨ q) ∧ (¬p ∨ r)) → q ∨ r  |

## WEEK 4:

- Our professor discussed about the different **Methods of Proof**.

### Methods of Proof

|  **TYPE**  |  **Way to solve**  |
| -------: | :--------------: |
|  _Direct Proof_  |  1. Assume that p is true  |
|   |  2. Show that q is true (based on 1.)  |
|  _Proof by Contraposition_  |  1. Assume ¬q is true |
|    |  2. Show that ¬p is also true |
|  _Vacuous Proof_  |  Show that the p is false to make p → q true|
|  _Trivial proof_  |  Show that q is true, it follows that p → q is also true  |
|  _Proof by Contradiction_  |  1. Assume that the premise is not true |
|   |  2. Show that 1. will end up in a contradiction |
|  _Proof by Equivalence_  |  Prove that p → q and q → p is true using any of the previous methods of proof|

## Week 5:
Mathematical Induction
  - The **principle of mathematical induction** states that: "If it starts true and its stay true then it's always true."
  - **Mathematical induction** can be inferred to as a **domino effect**. 
    - (1) The first domino falls. 
    - (2) When any domino falls, the next domino falls.
    - Therefore, all dominos will fall!
  - Steps in constructing Mathematical Induction:
    1. Show (not ~~assume~~) P(1) or P(0) to be true.
    2. Assume P(k) is true.
    3. Show P(k+1) to be true.
