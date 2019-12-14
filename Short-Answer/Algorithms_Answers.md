#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

```python
a)  a = 0
    while (a < n * n * n):
      a = a + n * n
```

a) O(n)
    It's a single loop that runs n times. 

```
b)  sum = 0
    for i in range(n):
      j = 1
      while j < n:
        j *= 2
        sum += 1
```

b) O(n^3)
    At first I thought it might be n(n^4) because there are technically 4 nested loops, right? But I think sum is incrementing 1 per run, so it will stop at 10 regardless... right?
    So only 3 loops are running in linear time...

```
c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0

      return 2 + bunnyEars(bunnies-1)
```

c) O(n)
    It's a recursive function.

## Exercise II


