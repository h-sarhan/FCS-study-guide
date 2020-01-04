## Fundamentals of Computer Science Study Guide



### Books

1. Rosen, K.H. *Discrete Mathematics and its Applications, Global Edition* [Direct Link](https://www.dawsonera.com/abstract/9780077151515)
2. Sipser, M. *Introduction to the theory of computation* PDF excerpts are provided on Coursera, however I suggest getting the book, because we only have access to chapter 1. The international edition can be found for cheap. [Link](https://biblio.co.uk/book/introduction-theory-computation-3-e-michael/d/813674725) 
3. Hopcroft, J., R. Motwani and J.D. Ullman *Introduction to automata theory, languages and computation* PDF Excerpts are provided on Coursera.
4. Forbes, M. *A theoretical introduction to Turing Machine* [Direct Link](https://www.dawsonera.com/abstract/9788132316909)
5. Kozen, D.C. *Automata and Computability*. PDF excerpts are provided on Coursera
6. Chang, S. (ed) *Data structures and algorithms* [Direct Link](https://ebookcentral.proquest.com/lib/londonww/detail.action?docID=1223927)

### Topics Covered

* Discrete Math Prerequisites
  * Logic
  * Proofs:
    * Direct Proof
    * Proof by Contraposition
    * Proof by Contradiction
    * Proof by Induction
  * Combinatorics
* Automata Theory
  * Finite State Automata
    * Deterministic
    * Nondeterministic
  * Regular Languages
    * Regular Expressions
  * Non-Regular Languages*
    * Pumping Lemma
    * Context-Free Grammars
  * Turing Machines*
* Algorithms
  * Algorithm Complexity
  * Algorithms Covered:
    * Insertion Sort
    * Bubble Sort
    * Heap Sort
    * Quick Sort
    * Merge Sort
    * Binary Search
    * Gale-Shapley
  * Master Theorem

*Consult external resources because these topics are not explained well in the lectures

### Topic Map

<img src="/FCS-concept-map.png" alt="Topic Map" style="zoom:150%;" />



### Suggested Reading List

| Week    | Topic                                   | Reading                                                      |
| ------- | --------------------------------------- | ------------------------------------------------------------ |
| 1 & 2   | Logic                                   | **Rosen**:<br />Chapter 1.1 - 1.4, <br />1.5 (optional)      |
| 3 & 4   | Proofs                                  | **Rosen**:<br />Chapter 1.8,<br />1.9 (optional, to practice proof-writing)<br />5.1,<br />5.3 (optional, but highly recommended to get more comfortable with recursion) |
| 5 & 6   | Combinatorics                           | **Rosen**:<br />Chapter 6.1 - 6.3                            |
| 7 & 8   | Automata Theory: DFA and NFA            | **Sipser**: <br />Chapter 1.1, 1.2                           |
| 9 & 10  | Automata Theory: Regular Languages      | **Sipser**:<br />Chapter 1.3, 1.4                            |
| 11 & 12 | Automata Theory: Non-Regular Languages* | **Sipser**:<br />Chapter 2.1 (More concise and easier to understand than Hopcroft reading)<br />**Hopcroft**:<br />Chapter 5<br />Chapter 7.1 (Covers Chomsky Normal Form) |
| 13 & 14 | Automata Theory: Turing Machines*       | **Forbes:**<br />Chapter 1 (I found this book to be unreadable. Read Sipser or Hopcroft instead)<br />**Kozen:**<br />Lecture 32<br />**Sipser:**<br />Chapter 3.1 (Optional)<br />**Hopcroft:**<br />Chapter 8.1, 8.2 (Optional) |
| 15 & 16 | Algorithms I                            | **Rosen:**<br />Chapter 3.1<br />**Chang:**<br />Chapter 8, 9 |
| 17 & 18 | Algorithms II                           | **Rosen**:<br /> 5.4                                         |
| 19 & 20 | Algorithms: Complexity                  | **Rosen**: <br />Chapter 3.2, 3.3 (both optional)<br />**Chang:**<br />Chapter 2,<br />3 (optional) |

**The lectures in weeks 11 - 14 (covering non-regular languages and Turing machines) are exceptionally poor so I suggest consulting the resources below*

### Resources

[Lecture notes](https://github.com/world-class/REPL/blob/master/notes/fundamentals_of_computer_science/students_notes/felipe_balbi/notes.pdf) by Felipe Balbi

##### Writing Proofs

1. The exercises in chapters 1.8, 1.9, and 5.1of the Rosen book give you the opportunity to practice proof-writing. Check your answers [here](https://www.slader.com/textbook/9780071315012-discrete-mathematics-and-its-applications-global-edition-7th-edition/)
2. [A Guide to Proof-Writing](https://www.cs.ucy.ac.cy/~dzeina/courses/epl111/proofwriting.pdf)
3. [Techniques for Proof-Writing](http://math.umaine.edu/~weiss/TechniquesForProof.pdf)
4. The Stanford CS103 [website](http://web.stanford.edu/class/cs103/) has many resources related to writing proofs

##### Automata Theory

1. Practice designing automata, regular expressions, grammars, and Turing machines by solving homework problems in the Automata Theory MOOC (#5 below) or the Sipser book. Check your answers [here](https://www.slader.com/textbook/9781285401065-introduction-to-the-theory-of-computation-3rd-edition/)
2. The Stanford CS103 [website](http://web.stanford.edu/class/cs103/) also has very well made and detailed slides covering Finite State Automata, Regular Expressions, Context-Free Grammars, and Turing Machines
3. [Theory of Computation lectures by UC Davis](https://www.youtube.com/playlist?list=PLslgisHe5tBM8UTCt1f66oMkpmjCblzkt). Follows the Sipser book. 
4. [NESO Academy Theory of Computation playlist](https://www.youtube.com/playlist?list=PLBlnK6fEyqRgp46KUv4ZY69yXmpwKOIev) 
5. [Stanford Automata Theory MOOC](https://lagunita.stanford.edu/courses/course-v1:ComputerScience+Automata+SelfPaced/about). Follows the Hopcroft book. Includes homework as well.

##### Algorithms

There are many resources to learn algorithms online here is a few of them:

1. [Khanacademy](https://www.khanacademy.org/computing/computer-science/algorithms)
2. [Visualgo](https://visualgo.net/en)
3. [GeeksforGeeks](https://www.geeksforgeeks.org/)
4. [Interview Cake sorting algorithms reference](https://www.interviewcake.com/sorting-algorithm-cheat-sheet), [Binary Search reference](https://www.interviewcake.com/concept/python/binary-search) 
5. [Algorithms Youtube Playlist](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O)
6. We also have access to CLRS, a popular algorithms textbook. [Direct Link](https://www.dawsonera.com/abstract/9780262270830) 
   The chapters relevant to this course are: 2, 3, 4.5, 4.6, 6, 7
