# Systems Engineering Glossary: Columnar Vectorized Query Engine

### Columnar Storage
Data storage layout organizing table data by columns rather than rows for high compression and scan throughput.

### Vectorized Execution
Processing arrays of data (vectors) in a single operator iteration, keeping data resident in L1/L2 CPU caches.

### Morsel-Driven Parallelism
Work-stealing execution framework dynamically assigning fixed-size data blocks to worker threads.

### Late Materialization
Delaying the reconstruction of row tuples until the final projection stage of query execution.
