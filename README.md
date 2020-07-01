# HPL-and-STREAM
HPL and STREAM (synthetic benchmarks)

This test involves running HPL (version 2.3) and STREAM (version 5.10). 

Both HPL and STREAM should be compiled using the CentOS 8 included version of gcc and BLAS. MPI version for HPL should be OpenMPI 3.1.4.

Single node benchmarking results for both HPL and STREAM must be provided for 

- CPU nodes
- GPU nodes
- High Memory nodes

For HPL, additionally, the (projected) results for 

- an interconnnect island
- the full solution

should be supplied.

Please also confirm library versions and compiler options used.

As part of acceptance testing, we will be verifying the submitted results; results measured on the delivered cluster must be within 10% of the submitted values.

Note that we will also, as part of acceptance testing, run HPL compiled using the Intel commpiler, Intel MPI, and MKL.
