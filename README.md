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

## WEEK 5
-This week, we solved more problems about methods or proofs.
    - If _n_ is a positive integer, then _n_ is odd if and only if _n^2_ is odd.
    - For any natural number _n_, _n_ is even if and only if _n^2_ is even.
    - Show that these statements about the integer _n_ are equivalent:
        - P1: _n_ is even
        - P2: _n-1_ is odd
        - P2: _n^2_ is even
    - Prove or disprove the following theorem: 
        - Every positive integer is the sum os the squares of two integers
    
* **MATHEMATICAL INDUCTION**
    - We are given a sequence of propositions that we would like to prove.
    - The sequence:
        - _P(1) P(2) P(3) P(k) P(k+1)_
    - Steps:
        1. Basis step: _P(1)_ is shown to be true
        2. Do the inductive step
    - Example: Prove _P(n) = 1 + 2 + 3 + ... + n = n(n+1)/2_
 
## WEEK 6
This week, we have some sort of continuation to Sets lessons, which is called Cardinality, and a new topic about Functions.

**Cardinality**
 - The number of elements it contains
 - If S is a set, we denote its cardinality by writing |S|
 - Examples:
   - |{a, b, c, d, e}| = 5
   - |{{a, b}, {c, d, e, f, g}, {h}}| = 3
   - |{1, 2, 3, 3, 3}| = 3
   - |{n ∈ N| n < 137}| = 137 (Zero is counted)
   
   - |N| = ℵ₀ (Aleph-zero, aleph-naught, "infinity")
   - |Even| = ℵ₀
   - |ℤ| = ℵ₀

**Function**
 - Let A & B be sets. A function f from A to B is an assignment of **exactly one** element of B to each element of A
 - We write f: A → B or f: A to B (Note: **to** is not an implication)
    - A for domain
    - B for Co-Domain (Can be called as **Range** when a particular subset B is connected from set A)
 - Image:
 
 - Examples:

f(x) = x^2 (Domain
x ∈ ℤ
f: ℤ to ℤ+ (Co-domain; not shown)
"Perfect Square" (Range; not shown)

int floor (float x) {
  }
Domain: float x (float → ℝ) ℝ
Range: int floor (int → ℤ) ℤ

 - Types of Function:
    - One-to-One (Injective) - ∀x∀y(f(x)=f(y) → x=y) and ∀x∀y(x≠y → f(x)≠f(y))
    - Onto (Surjective) Range = Co-domain (and must be filled)
    - One-to-one and Onto (Bijection)

THE SUBMISSION OF THE "PROJECT, 0-0 (Individual)" IS DUE ON **MARCH 1, 2016**
##WEEK 7:

**Algorithm**

 - This is a finite set of precise instructions for performing a computation or for solving a problem.
 - Ex: Describe an algorithm for finding the maximum (largest) value in a finite sequence of integers.
 
    Procedure: Find Max
    Input: {a1, a2, ..., ai, ..., an}
    Output: maximum, max

          1. max = a1
          2. for i: 2 to n
          3.     if (max < ai)
          4.         max = ai

 - **Preconditions** - Statements that describe valid input
    - Ex: (a1, a2, : : :, an) ∈ ℤ
 - **Postconditions** - Conditions that the ouput should satisfy when the program has run
    - Ex: Output: max is the largest element

 - Properties of Algorithm:
    - Input - An algorithm has input values from a specified set (set for the *Precondition*)
    - Output - From each set of input values an algorithm produces output values from a specified set (set for the *Postcondition*)
    - Definiteness - The steps of an algorithm must be defined precisely
    - Correctness - An algorithm should produce the correct output values for each set of input values
    - Finiteness - An algorithm should produce the desired output after a finite number of steps
    - Generality - The procedure should be applicable for all problems of the desired form, not just for a particular set of input
 
 - **Pseudocode** - A detailed step in the process of developing an algorithm

 - **Searching Algorithms**
    - The problem of locating an element in an ordered list
    - Locate an element x in a list of distinct elements a1, a2,..,an, or determine that is is not in the list
    
    - Types of Searching Algorithms:

 Linear Algorithm

          Procedure: Linear Search
          Input: {a1, a2, ..., ai, ..., an}
                 (x: searched element)
          Output: location, loc
                   {1, ..., n}
                   { = -1 if not found}

           1. loc = -1
           2. for i: 1 to n
           3.     if (x==ai)
           4.         loc = i
           
           OR
          
           1. i = 1
           2. while (i ≤ n ∧ x ≠ y)
           3.        i = i + 1
           4. if (i ≤ n)
           5.     loc = i
           6. else loc = -1

 Binary Algorithm
 
           Procedure: Binary Search
           Input: {a1, a2, ..., ai, ..., an}
                   (x: searched element)
           Output: location, loc
 
           1. i = 1
           2. j = n
           3. while ( i < j) {
           4.        mid = (i + j)/2
           5.        if (x > mid)
           6.            i = mid + 1
           7.        else j = mid }
           8.  if (x==ai)
           9.  loc = i
           10. else loc = -1
 
##WEEK 8:

This week we continues our topic we have discussed last week. Here are more examples of the algorithms that are needed to be thoroughly remembered and understand in order to figure out the specific procedures.

 - **Sorting Algorithms** - The algorithm of putting elements in increasing (or decreasing) order

Bubble Sort

          Procedure: Bubble Sort
          Input: {a1, a2, ..., ai, ..., an}
          Output: (x1, x2, ..., xi, ..., xn)
                   x1 < x2 < ... < xn
 
          1. for j: 1 to n-1
          2.   for i: 1 to n-j
          3.       if (ai > ai + 1)
          4.         swap (ai, ai + 1)
          OR basically what it means:
          [temp = ai]
          [ai = ai + 1]
          [ai + 1 = temp]


Insertion Sort

          Procedure: Insertion Sort
          Input: {a1, a2, ..., ai, ..., an}
          Output: (x1, x2, ..., xi, ..., xn)
                   x1 < x2 < ... < xn

          1. for j = 2 to n
          2. {
          3. i = 1
          4.   while aj > ai
          5.     i = i + 1
          6.     m = aj
          7.     for k = 0 to j – i – 1
          8.       aj–k = aj–k–1
          9.      ai = m
          10. }


 - **Greedy Algorithm** - Selects the best choice at each step, instead of considering all sequences of steps that may lead to an optimal solution

Example: Find a change and number of coins for 68 cents.

P, N, P, Q
1, 1, 1, 2

Denomination:

C = { 25, 10, 5, 1}
x = amount

          Procedure: Greedy Algorithm
          Input: C = { 25, 10, 5, 1}, which is {c1, c2, ..., ci, ..., cn}
                 x: amount
          Output: number of coins, n

          1. n = 0
          2. for i: 1 to 4 (or any var)
          3.    while (x ≥ ci)
          4.      x = x - ci
          5.      n = n + 1
