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
## **Week 9:**
* The continuation of the lesson, Algorithm:
	* Algorithm 3:
	
			Bubble Sort
			
			Input: {A1,A2,.....,Ai,....An} ∈ all real numbers, n>=2
			Output: {X1,X2,....,Xi,...,Xn} where X1<X2<.....<Xn
			for j=1 to n-1
				for i=1 to n-j
					if(Ai>A(i+1))
					swap(Ai,A(i+1))

	* Algorithm 4:
	
			Insertion Sort
			
			Input:{A1,A2,.....,Ai,....An} ∈ n>=2
			for j=2 to n
			{
				i=1
				while Aj>Ai
					i=i+1
				m=Aj
				for k=0 to j-i-1
					A(j-k)=A(j-i-1)
				Ai=m
			}
			Output: {X1,X2,X3,....,Xn:increasing order}

		* Outer for-loop is responsible of the sorting.
		* Inner for-loop is responsible for swapping.

	* Algorithm 5:
	
			Greedy Algorithm
			- selects the best choice at each step, instead of considering all sequences of steps that may lead to an optional solution.
			- applied in optimization problems where a solution to the given problem either minimizes or maximizes the value of some parameter.
			
			Denomination 
				C={25,10,5,1}
				x=amount of memory
			for i=1 to r
				x=0
			while (x≥Ci)
				x=x-Ci
				n=n+1

## **Week 10:**
* This week, we were introduced to growth of functions.
	* Using Big-O, Big-Ω and Big-ϴ
	* In Big-O, we are looking for the upper bound size of f(x).
	* In Big-O, let f and G be functions from Real numbers to Real numbers where f(x) is O(g(x)) if there are constants C and k such that:
	
			|f(x)| ≤ C|g(x)| where x > k
			C and k are the witnesses of Big-O

		* Example:
			
				x^2 + 2x + 1 is O(x^2) 
				x^2 + 2x + 1 is O(x^3)
				x^2 + 2x + 1 is O(x^4)

	* Same as in Big-Ω, but in this function, we are looking for the lower bound of f(x).
	
		* Example:
		
				x^2 + 2x + 1 is Ω(x^2)
				x^2 + 2x + 1 is Ω(x)

	* Lastly, in Big-ϴ, we are looking for both the lower and upper bound size of f(x).
	
		* Example:
		
				x^2 + 2x + 1 is ϴ(x^2)

		* There is only one answer in Big-ϴ.

* Next, Time Complexity in Algorithm, and Division and Modulo Operator
	
	* Time Complexity
		* can be expressed in terms of the number of operations used by the algorithms.
		* number of comparisons will be used as the measure of the time complexity.
	
		| Complexity | Terminology |
		| :---: | :---: |
		| ϴ(1) | constant complexity |
		| ϴ(logn) | log complexity |
		| ϴ(n) | linear complexity |

		* Time complexity of finding max comparison: 2n-1, ϴ(n)
		* Time complexity of linear search: 2n+2, ϴ(n)
	
	* Division and Modulo
	
			* Example:
				Let a = integer, d = positive integer
				Unique integers Q and r
					with 0<=r<d such that a=dQ+r
				9 mod 2 = 1 (r)
				9 div 2 = 4 (Q)
				a=d*Q+r
				a=2*4+1
				a=9

	* Last topic for quiz 2 was Ceasar Cipher.
	
			* How can you make your message secret?
				Example:
				LOVE = ORYH
				(p+3) mod 26
## **WEEK 11:**

**Graph Theory**

- Graphs - Discrete structures consisting of vertices and edges that connect these vertices.

Example:



 - A graph G = (V, E)  consist of V, a nonempty set of vertices (or nodes), and R, a set of edges. Each edge has either one or two verices associated with it, called its endpoints.
 
Using the example above:

G = (V, E)
V = {L, R, I, O}
E = {(L, R), (L, I), (I, O), (O, R), (I, R)}

Example 2:




G = (V, E)
V = {L, R, I, *G*}
E = {...} ( G is not connected therefore not included in the edges)

Basic Terminology:

 - The degree of a vertex in an udirected graph is the number of edges incident with it, except that a loop at a vertex contributes twice to the degree of that vertex.

Handshaking Theorem:

 - Let G = (V, E) be an undirected graph with e edges, then
    - 2e = ∑deg(v), where
        - v = vertices
        - deg = degrees of the vertices
        - e = edges

Example: How many edges are there in the graph with 10 vertices each of degree six?

          2e = ∑deg(v)
          2e = 6(10)
          2e = 60
          e = 30
       There are total of 30 edges in the graph with 10 vertices with a degree of 6 each.


- A subgraph of a graph G = (V, E) is a graph H = (W, F), where W ⊆ V and F ⊆ E. A subgraph H of G is a proper subgraph of G if H ≠ G.
- Example: 

G1 subgraph G

G = {V, E}
G1 = {G1, E1}

V1 ⊆ V
E1 ⊆ E

V1 = {G, J}
E1 = {(G, J), (J,G)}

- The Union of the two simple graphs G1 = (V1, E1) and G2 = (V2, E2) is the simple graph with the vertex set V1 ∪ V2 and the edge set E1 ∪ E2.



- The Intersection of the two simple graphs G1 = (V1, E1) and G2 = (V2, E2) is the simple graph with the vertex set V1 ∩ V2 and the edge set E1 ∩ E2.



**Paths(Route)**

- A path is a sequence of edges the begins on one vertex.

Euler Circuit and Paths:

- Euler Circuit
    - Covers all the **edges** by crossing the path once and only once; begins and ends with the same vertex.
    - All vetices(nodes) have **even** degrees.
- Euler Path
    - Covers all the **edges** by crossing the path once and only once; starts at one vertex but ends on a different vertex.
    - **Exactly two** vertices(nodes) have **odd** degrees.

Examples:

G1 = Euler Path
G2 = Euler Path
G3 = None

Hamilton Paths and Circuits:

- Hamilton Circuit
    - Covers all the **vertices** by crossing the path once and only once; begins and ends with the same vertex.
    - (It is usually found on closed circuits)
- Hamilton Path
    - Covers all the **vertices** by crossing the path once and only once; starts at one vertex but ends on a different vertex.
    - (It is possible if the circuit is open; it can have a pendant)

**Matrices of Graphs**

ai = 
- **1** if (vi, vj) has a connection
- **0** if otherwise

Example:




Matrix

0 1 1 1
1 0 1 0
1 1 0 0
1 0 0 0

**Isomorphism of Graphs** 

- Graph G = Graph H
- If and only if V1 = V2 and E1 = E2 by connection or pinpointing the location each of the vertices
- They should have the same number of vertices and edges

Example:





G = H
U1 <=> V1
U2 <=> V4
U3 <=> V3
U4 <=> V2


**Planar Graphs**

(Untangle the rope)

- No edges and vertices should cross or intersect
- The **tangles** can be removed

- Kuratowski's Theorem:
    - The graph is non-planar if the subgraph of the graph is K5 or K3,3

**Euler's Formula:**

       r = e - v + 2


##**WEEK 12:**

Last time on Kuratowski's Theorem...

- Is the Petersen graph shown planar?
    - No
- Is it a K3,3 or K5?
    - K3,3

Techniques to determine the correct subset in Kuratowski's Theorem:

- Technique 1: Compare the degrees of each vertices on both comparing graphs. If they have the same number of degrees, it is most likely that's the subgraph of one of the non-planar graphs (K3,3 when the degrees of each vertices is 3, and K5 when it's 5).
- Technique 2: To check if it is the correct non-planar subgraph, try to delete and compare the similarities by rearranging the vertices. Also, there will be times that there are more vertices, but it can form the figure of the subgraph, thus the graph formed is homeomorphic.


Homeomorphic graph - can be obtained from the same graph by elementary subdivision.
- Elementary Subdivision - remove the necessary vertex between the two vertices that needs to be connected, add the edge that needs to be connected.

**Graph Coloring**

Consider a map (found on the powerpoint)

c(G)= 4 (Chromatic Value)

Euler Circuit - Linear
Chromatic Number - Expenential

    - Technique - Biparite (K3,3) = 2 colors

Four Color Theorem:

- When planar, max color = 4

    - Technique - Kn = n (Parites)
    - Technique - Codd = 3, Ceven = 2 (Circles)
    - Sn = 2 (Stars)
    - Wodd = 3, Weven = 4 (Wheels)

**Trees**

- A tree is connected undirected graph with no simple circuits
- In a proper organized uprooted tree:
    - The topmost part is the root
    - The lowest parts are the children

Why Study Tees

- Binary Search
- Data Transmission and Storage
- Huffman Coding

Examples found the slides (Answers)

- G1
- G2
- G4 (is called *forest*)

A tree is a subset to a connected graph

*Rooted Trees:*

- Internal Vertices - vertices w/ children
- Leaves - vertices w/o children
 
*M-ary Tree:*

- A tree with uniform children
 
*Ordered rooted tree:*

- A rooted tree where the children of each internal vertex are ordered.

Properties of Trees:

- A tree with n vertices has **n - 1** edges.
- A full m-ary tree with i internal vertices contains **n = mi + 1** vertices.
- A full m-ary tree with:
    - **n** vertices has **i = (n - 1)/ m** internal vertices and **l = [(m - 1)n + 1 ]/ m** leaves,
    - **i** internal vertices has **n = mi + 1** vertices and **I = (m - 1)i + 1** leaves,
    - **l** leaves has **n = (ml - 1 )/(m - 1)** vertices and **i = (l - 1 )/(m - 1)** internal vertices.

- Example: (Answers)
    - leaves = l = 100
    - m-ary = m = 4
    - Using the Case III property:
       - n = (399)/(3) = 133 total people seen it
       - i = (99)/(3) = 33 sent the letter

**Modeling Computation**

Given a task, two questions arise.

- Can it be carried out using a computer?
- If yes, how can the task be carried out?

*IBM Deep Blue vs Kasparov**

Types of modeling computation:

- Grammars
- Finite Machine
- Turring Machine
 
*Grammars* 
- are used to generate the words of a language and to determine whether a word is in a language
- formal languages, which are generated by grammars, provide models for both natural languages, such as English, and for programming languages, such as Pascal, Prolog, Co, and Java
- They are extremely important in the construction and theory of compilers

- Compiler - a program that reads a program written in a source language and traslates it into an equivalent program in a target language
 

Syntax vs. Semantics
- The syntax of a natural language is extremely complicated
- In computation, formal language...

Language and Grammars 

- Construct a derivation tree
    - Vocabulary
    - Word
    - Derivation or Parse Tree

Automata Theory:

- Studies the laws of the computation
- Compose of State

- Finite Automation - provides the simpliest model of a computing device
    - Example: Used in Lexical Analyzers
  
        mkcz is a legal name
        69u is not


*Finite-State Machine*

M = (S, I, O, f, g, s0)

S - states (sets)
I - input alphabets (input)
O - output alphabets (ouput)
f - transition function (arrows)
g - output function
s0 - initial states

- That ends our class in DISMATH
- We also have an app that is due on Wednesday April 13, 2016
