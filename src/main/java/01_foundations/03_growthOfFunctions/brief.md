The order of growth of the running time of an algorithm, defined in Chapter 2,
gives a simple characterization of the algorithm’s efficiency and also allows us to
compare the relative performance of alternative algorithms. Once the input size n
becomes large enough, merge sort, with its ‚.n lg n/ worst-case running time,
beats insertion sort, whose worst-case running time is ‚.n2/. Although we can
sometimes determine the exact running time of an algorithm, as we did for insertion
sort in Chapter 2, the extra precision is not usually worth the effort of computing
it. For large enough inputs, the multiplicative constants and lower-order terms of
an exact running time are dominated by the effects of the input size itself.
When we look at input sizes large enough to make only the order of growth of
the running time relevant, we are studying the asymptotic efficiency of algorithms.
That is, we are concerned with how the running time of an algorithm increases with
the size of the input in the limit, as the size of the input increases without bound.
Usually, an algorithm that is asymptotically more efficient will be the best choice
for all but very small inputs.
This chapter gives several standard methods for simplifying the asymptotic analysis of algorithms. The next section begins by defining several types of “asymptotic notation,” of which we have already seen an example in ‚-notation. We then
present several notational conventions used throughout this book, and finally we
review the behavior of functions that commonly arise in the analysis of algorithms.

