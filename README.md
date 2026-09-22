# Algorithm Laboratory

A small, readable implementation lab for data structures, algorithms, and competitive-programming patterns.

The goal is not to collect code. It is to understand the invariant behind each algorithm, test it, and keep the implementation simple enough to reason about.

## Implemented

| Module | What it demonstrates |
|---|---|
| `binary_search.py` | first-true / first-false boundary search |
| `merge_sort.py` | divide-and-conquer sorting |
| `heap.py` | min-heap operations |
| `rabin_karp.py` | rolling-hash string matching |
| `graph.py` | BFS, DFS, and shortest paths |
| `dijkstra.py` | weighted shortest paths with a priority queue |

## Principles

- State the invariant before the loop.
- Prefer $O(n \log n)$ or better when the problem allows it.
- Test edge cases: empty input, duplicates, one element, disconnected graphs.
- Keep implementations dependency-free.

## Running

```bash
python -m pytest
```

## Roadmap

Dynamic programming, union-find, Fenwick trees, segment trees, string algorithms, and a small collection of Codeforces-style problems.
