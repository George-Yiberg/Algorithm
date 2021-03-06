This chapter will familiarize you with the framework we shall use throughout the
book to think about the design and analysis of algorithms. It is self-contained, but
it does include several references to material that we introduce in Chapters 3 and 4.
(It also contains several summations, which Appendix A shows how to solve.)
We begin by examining the insertion sort algorithm to solve the sorting problem
introduced in Chapter 1. We define a “pseudocode” that should be familiar to you if
you have done computer programming, and we use it to show how we shall specify
our algorithms. Having specified the insertion sort algorithm, we then argue that it
correctly sorts, and we analyze its running time. The analysis introduces a notation
that focuses on how that time increases with the number of items to be sorted.
Following our discussion of insertion sort, we introduce the divide-and-conquer
approach to the design of algorithms and use it to develop an algorithm called
merge sort. We end with an analysis of merge sort’s running time.