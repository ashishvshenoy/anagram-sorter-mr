# MapReduce application to sort a large corpus of Anagrams
MapReduce application that, given an input containing a single word per line, will group words that are anagrams of each other and sort the groups based on their size in descending order.

Example :


Input

abroad

early

natured

unrated

layer

aboard

untread

leary

relay

Intermediate Output

abroad aboard

early leary layer relay

natured unrated untread

Final Output (sorted in descending order of size)

early leary layer relay

natured unrated untread

abroad aboard

