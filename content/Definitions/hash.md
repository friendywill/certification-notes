a one-way input deterministic computation, that will generate some string

It is used when verifying the input has not changed, as even if one bit changes, the entire hash will as well.

The five basic requirements for a hash are:
- they accept input of any length
- they produce an output of fixed length, regardless of input size
- The hash value is relatively easy to compute
- The hash function is one way
- It must be collision free