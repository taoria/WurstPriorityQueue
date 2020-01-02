# Priority Queue For [Wurst](https://github.com/wurstscript)

**warning:** this is a hashtable simulated data structure.

## usage

to use priority queue,for example
```wurst
import PriorityQueue
PriorityQueue<int> pq = new PriorityQueue<int>((t1,t2)->t1-t2)
pq.enqueue(233)
pq.enqueue(455)

let res = pq.dequeue()
```

