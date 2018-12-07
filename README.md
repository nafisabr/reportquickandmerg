# reportquickandmerg
# comparision of quicksort and mergsort as the matter of time
# for sorting a list of numbers one way is to divide the list in two subunits and do it again and again till reach the only 2 num
# the bigger one could be find out
# then when we come through the last 2 num to the last 4 and then last 8 the subunit list will be sorted
# this is the overview of mergesort function
# inother hand another way of sorting called quicksort function is to consider one of the numbers in the list as a pivot
# then make two lists in right and left of that pivot 
# which means the lower values are added in left list and the higher ones are added to the right list
# the same happens to each right and lift lists as a new list till we see at last all the values are sorted
# now lets test the time to find out which of this two functions works faster 
# we will give each of the programs a random list of deferent ranges like 10,100,1000 
# keep doing it several times which this several times assigned as length and measure the time it takes to sort all of them
# as the result shows the seconds for each function:
# in most cases quick sort is faster but surprisingly in some cases mergsort is much more faster
# and that some cases are when the range in low and the length is high

# here is the comparison of the time result for quicksort and mergesort:

Length=10,Range=10 , Quicksort: 0.000132 , Mergesort: 0.000230, percent:       0.58
Length=10,Range=100 , Quicksort: 0.000129 , Mergesort: 0.000220, percent:       0.59
Length=10,Range=200 , Quicksort: 0.000121 , Mergesort: 0.000281, percent:       0.43
Length=10,Range=1000 , Quicksort: 0.000140 , Mergesort: 0.000223, percent:       0.63
Length=100,Range=10 , Quicksort: 0.002560 , Mergesort: 0.003391, percent:       0.75
Length=100,Range=100 , Quicksort: 0.001825 , Mergesort: 0.003413, percent:       0.53
Length=100,Range=200 , Quicksort: 0.001491 , Mergesort: 0.003480, percent:       0.43
Length=100,Range=1000 , Quicksort: 0.001841 , Mergesort: 0.003346, percent:       0.55
Length=1000,Range=10 , Quicksort: 0.124680 , Mergesort: 0.045843, percent:       2.72
Length=1000,Range=100 , Quicksort: 0.034858 , Mergesort: 0.046083, percent:       0.76
Length=1000,Range=200 , Quicksort: 0.027447 , Mergesort: 0.046133, percent:       0.59
Length=1000,Range=1000 , Quicksort: 0.024663 , Mergesort: 0.046087, percent:       0.54
Length=10000,Range=10 , Quicksort: 14.542730 , Mergesort: 0.760508, percent:      19.12
Length=10000,Range=100 , Quicksort: 1.374629 , Mergesort: 0.648589, percent:       2.12
Length=10000,Range=200 , Quicksort: 0.937674 , Mergesort: 0.627409, percent:       1.49
Length=10000,Range=1000 , Quicksort: 0.403089 , Mergesort: 0.602369, percent:       0.67
