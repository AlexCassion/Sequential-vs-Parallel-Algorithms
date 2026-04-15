While implementing the parallel version, we had some difficulty especially in merging the sorted chunks. It was easy to divide the data, but combining them correctly into one sorted list was more complicated than expected.

In searching, handling the correct index was also challenging since each process had its own part of the data. We had to adjust using offsets.

In terms of performance, parallel sorting only helped in large datasets. For smaller ones, sequential was still better. So I think parallelism is only good for heavy tasks.