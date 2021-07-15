# DAS-PageReplacementPolicy

**IMPLEMENTAION**

We have implemented 4 cache replacement policies:
1. Belady's OPT 
2. LRU
3. LFU
4. DAS (Dynamic and Stable) Cache Replacement Policy

**TRACE FILES**

We tested our code on the following trace files obtained from the references below:

http://www.cs.toronto.edu/~reid/csc150/02f/a2/traces.html
1. Sorting: http://www.cs.toronto.edu/~reid/csc150/02f/a2/sort1
2. LU Decomposition: http://www.cs.toronto.edu/~reid/csc150/02f/a2/lu
3. Matrix Multiply: http://www.cs.toronto.edu/~reid/csc150/02f/a2/mmout http://www.cs.toronto.edu/~reid/csc150/02f/a2/mmout1


https://cseweb.ucsd.edu/classes/fa07/cse240a/project1.html

Trace files download link: https://cseweb.ucsd.edu/classes/fa07/cse240a/proj1-traces.tar.gz

**STIMULATION**

We have uploaded 2 example trace file stimulations:

[Example_gcc.ipynb](https://github.com/VarshitMaisuriya/DAS-PageReplacementPolicy/blob/main/Example_gcc.ipynb)  and [Example_lu.ipynb](https://github.com/VarshitMaisuriya/DAS-PageReplacementPolicy/blob/main/Example_lu.ipynb)

Changing the file names we get the corresponding .csv files through which we can plot the data.

**OPTIMAL PARTITIONING**

We varied the partition size for LRU and LFU portion and obtained the results comparing which ratio works better for following traces.
