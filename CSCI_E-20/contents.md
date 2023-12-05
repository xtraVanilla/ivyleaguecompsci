```markdown
# Table of Contents

1. [Logical Thinking](#logical-thinking)
   1.1 [Formal Logic](#formal-logic)
   1.1.1 [Inquiry Problems](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.1.1.md)
   1.1.2 [Connectives and Propositions](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.1.2.md)
   1.1.3 [Truth Tables](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.1.3.md)
   1.1.4 [Logical Equivalences](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.1.4.md)

   1.2 [Propositional Logic](#propositional-logic)
   1.2.1 [Tautologies and Contradictions](#tautologies-and-contradictions)
   1.2.2 [Derivation Rules](#derivation-rules)
   1.2.3 [Proof Sequences](#proof-sequences)
   1.2.4 [Forward–Backward](#forward–backward)
   Exercises 1.2
   1.3 [Predicate Logic](#predicate-logic)
   1.3.1 [Predicates](#predicates)
   1.3.2 [Quantifiers](#quantifiers)
   1.3.3 [Translation](#translation)
   1.3.4 [Negation](#negation)
   1.3.5 [Two Common Constructions](#two-common-constructions)
   Exercises 1.3
   1.4 [Logic in Mathematics](#logic-in-mathematics)
   1.4.1 [The Role of Definitions in Mathematics](#the-role-of-definitions-in-mathematics)
   1.4.2 [Other Types of Mathematical Statements](#other-types-of-mathematical-statements)
   1.4.3 [Counterexamples](#counterexamples)
   1.4.4 [Axiomatic Systems](#axiomatic-systems)
   Exercises 1.4
   1.5 [Methods of Proof](#methods-of-proof)
   1.5.1 [Direct Proofs](#direct-proofs)
   1.5.2 [Proof by Contraposition](#proof-by-contraposition)
   1.5.3 [Proof by Contradiction](#proof-by-contradiction)
   Exercises 1.5

2. [Relational Thinking](#relational-thinking)
   2.1 [Graphs](#graphs)
   2.1.1 [Edges and Vertices](#edges-and-vertices)
   2.1.2 [Terminology](#terminology)
   2.1.3 [Modeling Relationships with Graphs](#modeling-relationships-with-graphs)
   Exercises 2.1
   2.2 [Sets](#sets)
   2.2.1 [Membership and Containment](#membership-and-containment)
   2.2.2 [New Sets from Old](#new-sets-from-old)
   2.2.3 [Identities](#identities)
   Exercises 2.2
   2.3 [Functions](#functions)
   2.3.1 [Definition and Examples](#definition-and-examples)
   2.3.2 [One-to-One and Onto Functions](#one-to-one-and-onto-functions)
   2.3.3 [New Functions from Old](#new-functions-from-old)
   Exercises 2.3
   2.4 [Relations and Equivalences](#relations-and-equivalences)
   2.4.1 [Definition and Examples](#definition-and-examples)
   2.4.2 [Graphs of Relations](#graphs-of-relations)
   2.4.3 [Relations vs. Functions](#relations-vs-functions)
   2.4.4 [Equivalence Relations](#equivalence-relations)
   2.4.5 [Modular Arithmetic](#modular-arithmetic)
   Exercises 2.4
   2.5 [Partial Orderings](#partial-orderings)
   2.5.1 [Definition and Examples](#definition-and-examples)
   2.5.2 [Hasse Diagrams](#hasse-diagrams)
   2.5.3 [Topological Sorting](#topological-sorting)
   2.5.4 [Isomorphisms](#isomorphisms)
   2.5.5 [Boolean Algebras‡](#boolean-algebras)
   Exercises 2.5
   2.6 [Graph Theory](#graph-theory)
   2.6.1 [Graphs: Formal Definitions](#graphs-formal-definitions)
   2.6.2 [Isomorphisms of Graphs](#isomorphisms-of-graphs)
   2.6.3 [Degree Counting](#degree-counting)
   2.6.4 [Euler Paths and Circuits](#euler-paths-and-circuits)
   2.6.5 [Hamilton Paths and Circuits](#hamilton-paths-and-circuits)
   2.6.6 [Trees](#trees)
   Exercises 2.6

3. [Recursive Thinking](#recursive-thinking)
   3.1 [Recurrence Relations](#recurrence-relations)
   3.1.1 [Definition and Examples](#definition-and-examples)
   3.1.2 [The Fibonacci Sequence](#the-fibonacci-sequence)
   3.1.3 [Modeling with Recurrence Relations](#modeling-with-recurrence-relations)
   Exercises 3.1
   3.2 [Closed-Form Solutions and Induction](#closed-form-solutions-and-induction)
   3.2.1 [Guessing a Closed-Form Solution](#guessing-a-closed-form-solution)
   3.2.2 [Polynomial Sequences: Using Differences‡](#polynomial-sequences-using-differences)
   3.2.3 [Inductively Verifying a Solution](#inductively-verifying-a-solution)
   Exercises 3.2
   3.3 [Recursive Definitions](#recursive-definitions)
   3.3.1 [Definition and Examples](#definition-and-examples)
   3.3.2 [Writing Recursive Definitions](#writing-recursive-definitions)
   3.3.3 [Recursive Geometry](#recursive-geometry)
   3.3.4 [Recursive Jokes](#recursive-jokes)
   Exercises 3.3
   3.4 [Proof by Induction](#proof-by-induction)
   3.4.1 [The Principle of Induction](#the-principle-of-induction)
   3.4.2 [Examples](#examples)
   3.4.3 [Strong Induction](#strong-induction)
   3.4.4 [Structural Induction](#structural-induction)
   Exercises 3.4
   3.5 [Recursive Data Structures](#recursive-data-structures)
   3.5.1 [Lists](#lists)
   3.5.2 [Efficiency](#efficiency)
   3.5.3 [Binary Search Trees Revisited](#binary-search-trees-revisited)
   Exercises 3.5

4. [Quantitative Thinking](#quantitative-thinking)
   4.1 [Basic Counting Techniques](#basic-counting-techniques)
   4.1.1 [Addition](#addition)
   4.1.2 [Multiplication](#multiplication)
   4.1.3 [Mixing Addition and Multiplication](#mixing-addition-and-multiplication)
   Exercises 4.1
   4.2 [Selections and Arrangements](#selections-and-arrangements)
   4.2.1 [Permutations: The Arrangement Principle](#permutations-the-arrangement-principle)
   4.2.2 [Combinations: The Selection Principle](#combinations-the-selection-principle)
   4.2.3 [The Binomial Theorem‡](#the-binomial-theorem)
   Exercises 4.2
   4.3 [Counting with Functions](#counting-with-functions)
   4.3.1 [One-to-One Correspondences](#one-to-one-correspondences)
   4.3.2 [The Pigeonhole Principle](#the-pigeonhole-principle)
   4.3.3 [The Generalized Pigeonhole Principle](#the-generalized-pigeonhole-principle)
   4.3.4 [Ramsey Theory‡](#ramsey-theory)
   Exercises 4.3
   4.4 [Discrete Probability](#discrete-probability)
   4.4.1 [Definitions and Examples](#definitions-and-examples)
   4.4.2 [Applications](#applications)
   4.4.3 [Expected Value](#expected-value)
   Exercises 4.4
   4.5 [Counting Operations in Algorithms](#counting-operations-in-algorithms)
   4.5.1 [Algorithms](#algorithms)
   4.5.2 [Pseudocode](#pseudocode)
   4.5.3 [Sequences of Operations](#sequences-of-operations)
   4.5.4 [Loops](#loops)
   4.5.5 [Arrays](#arrays)
   4.5.6 [Sorting](#sorting)
   Exercises 4.5
   4.6 [Estimation](#estimation)
   4.6.1 [Growth of Functions](#growth-of-functions)
   4.6.2 [Estimation Targets](#estimation-targets)
   4.6.3 [Properties of Big-Θ](#properties-of-big-Θ)

- [4.6 Estimation](#46-estimation)
  - [4.6.1 Growth of Functions](#461-growth-of-functions)
  - [4.6.2 Estimation Targets](#462-estimation-targets)
  - [4.6.3 Properties of Big-Θ](#463-properties-of-big-θ)
  - [Exercises 4.6](#exercises-46)

## Chapter 5 Analytical Thinking

- [5.1 Algorithms](#51-algorithms)

  - [5.1.1 More Pseudocode](#511-more-pseudocode)
  - [5.1.2 Preconditions and Postconditions](#512-preconditions-and-postconditions)
  - [5.1.3 Iterative Algorithms](#513-iterative-algorithms)
  - [5.1.4 Functions and Recursive Algorithms](#514-functions-and-recursive-algorithms)
  - [Exercises 5.1](#exercises-51)

- [5.2 Three Common Types of Algorithms](#52-three-common-types-of-algorithms)

  - [5.2.1 Traversal Algorithms](#521-traversal-algorithms)
  - [5.2.2 Greedy Algorithms](#522-greedy-algorithms)
  - [5.2.3 Divide-and-Conquer Algorithms](#523-divide-and-conquer-algorithms)
  - [Exercises 5.2](#exercises-52)

- [5.3 Algorithm Complexity](#53-algorithm-complexity)

  - [5.3.1 The Good, the Bad, and the Average](#531-the-good-the-bad-and-the-average)
  - [5.3.2 Approximate Complexity Calculations](#532-approximate-complexity-calculations)
  - [Exercises 5.3](#exercises-53)

- [5.4 Bounds on Complexity](#54-bounds-on-complexity)

  - [5.4.1 Algorithms as Decisions](#541-algorithms-as-decisions)
  - [5.4.2 A Lower Bound](#542-a-lower-bound)
  - [5.4.3 Searching an Array](#543-searching-an-array)
  - [5.4.4 Sorting](#544-sorting)
  - [5.4.5 P vs. NP](#545-p-vs-np)
  - [Exercises 5.4](#exercises-54)

- [5.5 Program Verification](#55-program-verification)

  - [5.5.1 Verification vs. Testing](#551-verification-vs-testing)
  - [5.5.2 Verifying Recursive Algorithms](#552-verifying-recursive-algorithms)
  - [5.5.3 Searching and Sorting](#553-searching-and-sorting)
  - [5.5.4 Towers of Hanoi](#554-towers-of-hanoi)
  - [Exercises 5.5](#exercises-55)

- [5.6 Loop Invariants](#56-loop-invariants)
  - [5.6.1 Verifying Iterative Algorithms](#561-verifying-iterative-algorithms)
  - [5.6.2 Searching and Sorting](#562-searching-and-sorting)
  - [5.6.3 Using Invariants to Design Algorithms](#563-using-invariants-to-design-algorithms)
  - [Exercises 5.6](#exercises-56)

## Chapter 6 Thinking Through Applications

- [6.1 Patterns in DNA](#61-patterns-in-dna)

  - [6.1.1 Mutations and Phylogenetic Distance](#611-mutations-and-phylogenetic-distance)
  - [6.1.2 Phylogenetic Trees](#612-phylogenetic-trees)
  - [6.1.3 UPGMA](#613-upgma)
  - [Exercises 6.1](#exercises-61)

- [6.2 Social Networks](#62-social-networks)

  - [6.2.1 Definitions and Terminology](#621-definitions-and-terminology)
  - [6.2.2 Notions of Equivalence](#622-notions-of-equivalence)
  - [6.2.3 Hierarchical Clustering](#623-hierarchical-clustering)
  - [6.2.4 Signed Graphs and Balance](#624-signed-graphs-and-balance)
  - [Exercises 6.2](#exercises-62)

- [6.3 Structure of Languages](#63-structure-of-languages)

  - [6.3.1 Terminology](#631-terminology)
  - [6.3.2 Finite-State Machines](#632-finite-state-machines)
  - [6.3.3 Recursion](#633-recursion)
  - [6.3.4 Further Issues in Linguistics](#634-further-issues-in-linguistics)
  - [Exercises 6.3](#exercises-63)

  - [6.4 Discrete-Time Population Models](#64-discrete-time-population-models)

    - [6.4.1 Recursive Models for Population Growth](#641-recursive-models-for-population-growth)
    - [6.4.2 Fixed Points, Equilibrium, and Chaos](#642-fixed-points-equilibrium-and-chaos)
    - [6.4.3 Predator–Prey Systems](#643-predatorprey-systems)
    - [6.4.4 The SIR Model](#644-the-sir-model)
    - [Exercises 6.4](#exercises-64)

  - [6.5 Twelve-Tone Music](#65-twelve-tone-music)
    - [6.5.1 Twelve-Tone Composition](#651-twelve-tone-composition)
    - [6.5.2 Listing All Permutations](#652-listing-all-permutations)
    - [6.5.3 Transformations of Tone Rows](#653-transformations-of-tone-rows)
    - [6.5.4 Equivalence Classes and Symmetry](#654-equivalence-classes-and-symmetry)
    - [Exercises 6.5](#exercises-65)

## Hints, Answers, and Solutions to Selected Exercises

- [1.1 Formal Logic](#11-formal-logic-1)
- [1.2 Propositional Logic](#12-propositional-logic-1)
- [1.3 Predicate Logic](#13-predicate-logic-1)
- [1.4 Logic in Mathematics](#14-logic-in-mathematics-1)
- [1.5 Methods of Proof](#15-methods-of-proof-1)
- [2.1 Graphs](#21-graphs-1)
- [2.2 Sets](#22-sets-1)
- [2.3 Functions](#23-functions-1)
- [2.4 Relations and Equivalences](#24-relations-and-equivalences-1)
- [2.5 Partial Orderings](#25-partial-orderings-1)
- [2.6 Graph Theory](#26-graph-theory-1)
- [3.1 Recurrence Relations](#31-recurrence-relations-1)
- [3.2 Closed-Form Solutions and Induction](#32-closed-form-solutions-and-induction-1)
- [3.3 Recursive Definitions](#33-recursive-definitions-1)
- [3.4 Proof by Induction](#34-proof-by-induction-1)
- [3.5 Recursive Data Structures](#35-recursive-data-structures-1)
- [4.1 Basic Counting Techniques](#41-basic-counting-techniques-1)
- [4.2 Selections and Arrangements](#42-selections-and-arrangements-1)
- [4.3 Counting with Functions](#43-counting-with-functions-1)
- [4.4 Discrete Probability](#44-discrete-probability-1)
- [4.5 Counting Operations in Algorithms](#45-counting-operations-in-algorithms-1)
- [4.6 Estimation](#46-estimation-1)
- [5.1 Algorithms](#51-algorithms-1)
- [5.2 Three Common Types of Algorithms](#52-three-common-types-of-algorithms-1)
- [5.3 Algorithm Complexity](#53-algorithm-complexity-1)
- [5.4 Bounds on Complexity](#54-bounds-on-complexity-1)
- [5.5 Program Verification](#55-program-verification-1)
- [5.6 Loop Invariants](#56-loop-invariants-1)
- [6.1 Patterns in DNA](#61-patterns-in-dna-1)
- [6.2 Social Networks](#62-social-networks-1)
- [6.3 Structure of Languages](#63-structure-of-languages-1)
- [6.4 Discrete-Time Population Models](#64-discrete-time-population-models-1)
- [6.5 Twelve-Tone Music](#65-twelve-tone-music-1)
```
