# kata-seed
.NET Start-Project, Setting up Testing and Package-Management

## Priority Queue
> source: http://ccd-school.de/coding-dojo/class-katas/priority-queue/

Implement a class representing a queue.
Each element of this queue has a priority.
Elements having a higher priority always stay above of those having a lower priority.
When to elements have the same priority the element added first to the queue is prior to the other element.

| Action                     | Queue                          |
|----------------------------|--------------------------------|
| `new PriorityQueue<int>()` |                                |
| `Enqueue(1, 5)`            | (1, 5)                         |
| `Enqueue(2, 5)`            | (1, 5), (2, 5)                 |
| `Dequeue() -> 1`           | (2, 5)                         |
| `Enqueue(3, 7)`            | (3, 7), (2, 5)                 |
| `Enqueue(4, 7)`            | (3, 7), (4, 7), (2, 5)         |
| `Enqueue(5, 3)`            | (3, 7), (4, 7), (2, 5), (5, 3) |
| `Count() -> 4`             |                                |
> generated with: http://www.tablesgenerator.com/markdown_tables
