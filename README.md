
A cpp styled python containers pkg, including PriorityQueue:

![pq_intro](https://github.com/lbyxiafei/priority_queue/blob/main/img/pq_intro.png)

# Usage

```bash
pip install stlcontainers
```

PriorityQueue:

```python
from stlcontainers import PriorityQueue

# default max heap
q = PriorityQueue([2,1,3,5,4])
q.push(1)
q.pop()
print(q.top())

# init min heap 
q = PriorityQueue([2,1,3], is_max_heap=False)
```

# Contact

lbyxiafei@gmail.com