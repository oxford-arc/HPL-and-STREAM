# HPL-and-STREAM
HPL and STREAM (synthetic benchmarks)

This test involves running HPL (version 2.3) and STREAM (version 5.10). 

Single node benchmarking results for both HPL and STREAM must be provided for 

- CPU nodes
- GPU nodes
- High Memory nodes

For HPL, additionally, the (projected) results for 

- an interconnnect island
- the full solution

should be supplied.

Please run one HPL problem, with one block size, of a suitable size and block size. 

Results of the form

````
================================================================================
T/V                N    NB     P     Q               Time                 Gflops
--------------------------------------------------------------------------------
WR00L2L2      202752   384     1     2            1819.13            3.05454e+03
````
for HPL and

````
-------------------------------------------------------------
Function      Rate (MB/s)   Avg time     Min time     Max time
Copy:      185505.3080       0.0071       0.0069       0.0085
Scale:     194850.2566       0.0069       0.0066       0.0089
Add:       198963.8957       0.0103       0.0096       0.0319
Triad:     203648.1813       0.0098       0.0094       0.0111
-------------------------------------------------------------
````

for STREAM should be included in the reply. Please confirm MPI version, library versions and compiler options used, along with a description how the problem was submitted to your test nodes, and include your 'HPL.dat' file in your response.

As part of acceptance testing, we will be verifying the submitted results; results measured on the delivered cluster must be within 10% of the submitted values.
