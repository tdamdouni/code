## Efficient generation of permutations

Originally published: 2008-12-22 06:11:55
Last updated: 2008-12-22 06:11:55
Author: nnarula 

This code builds an iterator on the fly that will successfully return unique permutations of n integers, m at a time (nPm).  It does not use recursion, so stack size is not a problem. 