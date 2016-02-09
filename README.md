# My Dismath Portfolio
Dismath Portfolio by Gian Chung
## WEEK 1
- This week, I learned that dismath or "Discrete Mathematics" is not really heavy on Algebra or Trigonometry
- It uses Logic or Mathematical proofs to prove somehing to be true. It uses "Mathematical Proof" to prove something.
- I also learned that Dismath is not an easy course. It takes skills to learn those things.
- I also learned that the is only true or false statements. No in between.
- I have also learned some weird symbols like ¬ for Negation, ∧ for conjunction, ∨ for disjunction,⊕ for exclusive disjunction,  →
 for implication, and ↔ for biconditional.

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) | 
- One of the hardest lesson that i have encountered was the implication.
- It is really tricky to learn that but it gets easier on the second or third try
- Here are some examples:
 - “p implies q”
    - “p only if q”
    - “if p, q”
    - “p is sufficient for q”
    - “a sufficient condition for q is p”
    - “q whenever p”
    - “q when p”
    - “a necessary condition for p is q”
    - “q is necessary for p”
    - “q follows from p”

## WEEK 2
  - I found Logical Equivalances to be harder than the truth table.
  - I learned about logical equivalances.
  - Logical equvalances is somewhat the same with the Algebraic Laws.
  
  | Name  |  Logical Equivalences |
| :-----: |:-------:|
| Identity Laws |  p v F = p |
                | p ∧ T = p |
| Domination Laws | p v T = T |
                  | p ∧ F = F |
| Negation Laws | p v ¬p = T |
                | p ∧ ¬p = F |
| Double Negation | ¬(¬p) = p |
| Idempolent Laws | p v p = p |
                  | p ∧ p = p |
| Commutative Laws | p v q = q v p |
                   | p ∧ q = q ∧ p |
| Associative Laws | (p v q) v r = p v (q v r) |
                   | (p ∧ q) ∧ r = p ∧ (q ∧ r) |
| Distributive Laws | p v (q r) = (p v q)  (p v r) |
                    | p ∧ (q v r ) = (p ∧ q) v (p ∧ r)
| DeMorgan's Laws | ¬(p ∧ q) = ¬p v ¬q |
                  | ¬(p v q) = ¬p ∧ ¬q |
| Absorption Laws | p v (p ∧ q) = p |
                  | p ∧ (p v q) = p |

 - We also did the homework that if superman exists or not.
 - The question is "Superman were able and willing to prevent evil, he would do so. 
  If Superman were unable to prevent evil, he would be impotent; if he were unwilling to prevent evil, he would be malevolent.
  Superman does not prevent evil. If Superman exists, he is neither impotent nor malevolent. Therefore, Superman does not exist.

## WEEK 3
  - We learned Predicate/Quantification logic.
  - Quantifier expresses that some property is true for some (∃) or all (∀) choices that could be made.
  - Existential Quantifier (∃x)
         " There exist "
  - Universal Quantifier (∀x)
         " For All "
  - We also learned Rules of Inference.
  - Rules of inference is Another set of things we should start familiarizing ourselve, 'the rules of inference'
  
  | Rules of Inference | | |
| :-----: |:-------:|:-----:|
| p | (p ∧ (p → q)) → q | Modus Ponens |
| p → q |
| ∴ q |
| ¬q | (¬q ∧ (p → q)) →  p | Modus Tollens |
| p → q |
| ∴ ¬p |
| p → q | ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
| q → r |
| ∴ p → r |
| p v q | ((p v q) ∧  p) → q | Disjunctive Syllogism |
| ¬p |
| ∴ q |
| p | p → (p v q) | Addition |
| ∴ p v q |
| p ∧ q | (p ∧ q) → p | Simplification |
| ∴ p |
| p | ((p) ∧ (q)) → (p ∧ q) | Conjunction |
| q |
| ∴ p ∧ q |
| p v q | ((p v q) ∧ (¬p v r)) → (q v r) | Resolution |
| ¬p v r |
| ∴ q v r |
  - We also learned that sometimes, it is easier to prove something using truth tables than Logical Equivalances.

## WEEK 4  
  - This week, we learned about method or proofs. the proofs are listed below.
1. Direct Proof 
        - Assume that p is true to show that q must also be true.
  2. Contraposition Proof
        - Assume that the negation of q must be true.
  3. Vacuous Proof 
        - Show that p is false because → q  must be true when p is false.
  4. Trivial Proof 
        - Show that q is true, it follows that p → q must also be true. q → (p → q) 
  5. Proof of Contradiction 
        - Assume that the negation of p must be true.
  6. Negation of Implication 
        - "If p is true, then q is true" is the statement "There is at least one case where p is true and q is false."
  7. Proof of Equivalence (Biconditionals) 
        - (p ↔ q) = (p → q) → (q → p)
- I am still trying to cope this topic. Even though we had exampples, it is still a little bit fuzzy.
