# Multithreading & Process Synchronization
Practicing process synchronization using the following schemes:
  1. Single-threaded
  2. Multithreaded where the parent waits for all the children
  3. Multithreaded where the parent continually checks on all children
  4. Multithreaded where the parent waits on a semaphore

## Compile
`g++ -O3 src/MTFindProd.c -o bin/MTFindProd -lpthread`

## Execute
`bin/MTFindProd <array size> <thread count> <index for zero>`
