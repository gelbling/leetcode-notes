### open var - keep track of OPEN parentheses

### closed var - keep track of CLOSED parentheses

- backtrack(open, closed)

### BASE CASE - open == closed == pairs of parentheses

- append to result

### CHOICE 1 - open < pais of parentheses

- add open parentheses
- backtrack
- pop

### CHOICE 2 - closed < open (meaning we can add closed parentheses)

- add closed parentheses
- backtrack
- pop
