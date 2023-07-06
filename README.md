# naderi-ruppert queue

In this work, we introduce a novel linearizable wait-free queue implementation. Linearizability and lock-freedom are standard requirements for designing shared data structures. To the best of our knowledge, all of the existing linearizable lock-free queues in the literature have a common problem in their worst case, called the CAS Retry Problem. We show that our algorithm avoids this problem with the helping mechanism which we use and has a worst-case running time better than prior lock-free queues. The amortized number of steps for an Enqueue or Dequeue in our algorithm is O(log^2 p + log q), where p is the number of processes and q is the size of the queue when the operation is linearized.

This work is published in PODC 2023: [https://dl.acm.org/doi/10.1145/3583668.3594565]. Thesis in YorkU library: [https://yorkspace.library.yorku.ca/xmlui/handle/10315/40975]. Also, you can find the slides in presentation folder.
