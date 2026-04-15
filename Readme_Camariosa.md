One thing I learned is that parallel is not always better. At first, I thought using multiple processes would automatically make everything faster, but that was not the case.

In smaller datasets, the parallel algorithms were slower because of the extra work like splitting data and managing processes. In larger datasets, especially in sorting, parallel became faster.

Searching did not improve much with parallelism. It actually became slower in our tests. I think it’s because the work per element is too small, so the overhead is not worth it.