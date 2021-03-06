This part will start you thinking about designing and analyzing algorithms. It is
intended to be a gentle introduction to how we specify algorithms, some of the
design strategies we will use throughout this book, and many of the fundamental
ideas used in algorithm analysis. Later parts of this book will build upon this base.
Chapter 1 provides an overview of algorithms and their place in modern computing systems. This chapter defines what an algorithm is and lists some examples.
It also makes a case that we should consider algorithms as a technology, alongside technologies such as fast hardware, graphical user interfaces, object-oriented
systems, and networks.
In Chapter 2, we see our first algorithms, which solve the problem of sorting
a sequence of n numbers. They are written in a pseudocode which, although not
directly translatable to any conventional programming language, conveys the structure of the algorithm clearly enough that you should be able to implement it in the
language of your choice. The sorting algorithms we examine are insertion sort,
which uses an incremental approach, and merge sort, which uses a recursive technique known as “divide-and-conquer.” Although the time each requires increases
with the value of n, the rate of increase differs between the two algorithms. We
determine these running times in Chapter 2, and we develop a useful notation to
express them.
Chapter 3 precisely defines this notation, which we call asymptotic notation. It
starts by defining several asymptotic notations, which we use for bounding algorithm running times from above and/or below. The rest of Chapter 3 is primarily
a presentation of mathematical notation, more to ensure that your use of notation
matches that in this book than to teach you new mathematical concepts.
Chapter 4 delves further into the divide-and-conquer method introduced in
Chapter 2. It provides additional examples of divide-and-conquer algorithms, including Strassen’s surprising method for multiplying two square matrices. Chapter 4 contains methods for solving recurrences, which are useful for describing
the running times of recursive algorithms. One powerful technique is the “master method,” which we often use to solve recurrences that arise from divide-andconquer algorithms. Although much of Chapter 4 is devoted to proving the correctness of the master method, you may skip this proof yet still employ the master
method.
Chapter 5 introduces probabilistic analysis and randomized algorithms. We typically use probabilistic analysis to determine the running time of an algorithm in
cases in which, due to the presence of an inherent probability distribution, the
running time may differ on different inputs of the same size. In some cases, we
assume that the inputs conform to a known probability distribution, so that we are
averaging the running time over all possible inputs. In other cases, the probability
distribution comes not from the inputs but from random choices made during the
course of the algorithm. An algorithm whose behavior is determined not only by its
input but by the values produced by a random-number generator is a randomized
algorithm. We can use randomized algorithms to enforce a probability distribution
on the inputs—thereby ensuring that no particular input always causes poor performance—or even to bound the error rate of algorithms that are allowed to produce
incorrect results on a limited basis.
Appendices A–D contain other mathematical material that you will find helpful
as you read this book. You are likely to have seen much of the material in the
appendix chapters before having read this book (although the specific definitions
and notational conventions we use may differ in some cases from what you have
seen in the past), and so you should think of the Appendices as reference material.
On the other hand, you probably have not already seen most of the material in
Part I. All the chapters in Part I and the Appendices are written with a tutorial
flavor.


