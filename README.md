# Algorithms-in-Molecular-Biology
Exercise in BWT index
It is an exercise for Data Science master and lesson Algorithms on Molecular Biology
Build the bwt index for a random reference genome with the help of syffix arrays.
Bowtie uses an algorithm of constructing suffix arrays in one block at a time.
This is the Karrkainen method that proposes to  randomly choose some splitter suffixes of the reference genome and sort them.
Then to create the blocks, all suffixes of the reference genome that belong to the boundaries which are defined by the sorted splitter suffixes, should be found.
At the end we construct the suffix array in each block and the respective BWT index
The algorithms for the construction of the BWT and the FM index are based on BenLangmed work.
