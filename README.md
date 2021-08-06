# DAS-PageReplacementPolicy

**IMPLEMENTAION**

We have implemented 5 cache replacement policies:
1. Belady's OPT 
2. LRU
3. LFU
4. DAS (Dynamic and Stable) Cache Replacement Policy
5. Adaptive DAS Cache Replacement Policy

**TRACE FILES**

We tested our code on the following trace files obtained from the references below:

Source1: http://www.cs.toronto.edu/~reid/csc150/02f/a2/traces.html
1. Sorting: http://www.cs.toronto.edu/~reid/csc150/02f/a2/sort1
2. LU Decomposition: http://www.cs.toronto.edu/~reid/csc150/02f/a2/lu
3. Matrix Multiply: http://www.cs.toronto.edu/~reid/csc150/02f/a2/mmout and http://www.cs.toronto.edu/~reid/csc150/02f/a2/mmout1


Source2: https://cseweb.ucsd.edu/classes/fa07/cse240a/project1.html

Trace files download link: https://cseweb.ucsd.edu/classes/fa07/cse240a/proj1-traces.tar.gz

**STIMULATION**

We have uploaded trace file stimulations in simulation folder comparing different page replacement policies on trace files.

**Results**

We have uploaded the results obtained by perfroming the above simulations in result folder.

**OPTIMAL PARTITIONING**

We varied the partition size for LRU and LFU portion and obtained the results by comparing different partitions for all traces.
We have uploaded the results by comparing the hit ratios for different partitions for all the traces mentioned above.

**Adaptive DAS**

We implemented our version of DAS wich works in adaptive nature by changing the size of the LRU and LFU portion depending upon the hit and miss.
We have uploaded the results comparing adaptive DAS and simple DAS for all the trace files mentioned above. 

**Latex Source Code**
https://www.overleaf.com/read/fwqbfqncprzb
