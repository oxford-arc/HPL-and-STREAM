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

HPL results of the form
================================================================================
T/V                N    NB     P     Q               Time                 Gflops
--------------------------------------------------------------------------------
WR00L2L2      202752   384     1     2            1819.13            3.05454e+03

should be included in the reply. Please confirm MPI version, library versions and compiler options used, along with a description how the problem was submitted to your test nodes, and include your 'HPL.dat' file in your response.

As part of acceptance testing, we will be verifying the submitted results; results measured on the delivered cluster must be within 10% of the submitted values.
