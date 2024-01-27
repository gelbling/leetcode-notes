### set to keep track of substring

### max size variable

### p1, p2

### while p2 < len(string)

- if current p2 val not in substring, add it, and increment p2

- else, update max size var, remove p1 val from set and increment p1
  - this is done until the repeated character is removed from the set

### return len(set)
