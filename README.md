# Parallel Programming
Course project for ECE 408: Applied Parallel Programming.

We implemented the following optimizations:

- Unroll / shared-memory Matrix multiply
- Shared Memory convolution
- Weight matrix (kernel values) in constant memory
- Tuning with restrict, loop unrolling
- Sweeping various parameters to find best values (block sizes, amount of thread coarsening)
- Input channel reduction: tree
- Input channel reduction: atomics
- Multiple kernel implementations for different layer sizes

Please refer to `ece408_src` for detailed implementation and [report](./report.pdf) for detailed explanation.