# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by 3 times, because each element is compared once.
The comparisons are proportional to the size of the list.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked
will grow by about 3 times, because it must find the
next lowest element by rerunning reigning champ.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by the sum from n to 3n of n, because it must compare the whole list,
then all but the 1st element, then all but the second, and so on until the list
is sorted.
[Justify, in about 2 sentences.]
