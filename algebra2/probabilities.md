# probabilities

## counting methods review
#### sample space, sets
S = {1,2,3,4,5,6}

A = {1,2,4}

B = {3,4,5}

C = {1,3,5,6}

| **union set** | **intersection set** | **complement** |
| :---: | :---: | :---: |
| A U B | C ∩ B | C' |
| {1,2,3,4,5} | {3,5} | {2,4} |

#### permutations and combinations
- counting methods of different items
  - to make a combination for 5 hats, 6 sunglasses, and 3 pairs of flipflops
  ```math
  5 * 6 * 3 = 90
  ```
  you can have 90 combinations of hats, sunglasses, and flip-flops

- permutations
when order matters
  ```math
  nPr = \frac{n!}{(n - r)!}
  ```

- combinations
when order doesn't really matter
  ```math
  nCr = \frac{n!}{(n - r)!r!}
  ```

- stuff
  n = number of objects
  r = number of objects selected

### probability
```math
P(Event) = \frac{N(E)}{N(S)}
```
P(E), is equal to the number of outcomes for that event to occur, N(E), divided by the total number of outcomes possible, N(S).

- summary
N(E) = number of outcomes for Event to occur
N(S) = number of outcomes possible

#### example
**coinflip**

say, we have a coin and we want to flip for heads. what are the chances we'll actually flip heads?

let N(E) = 1 (out of 2 options, h&t)
    N(S) = 2
```math
P(E) = \frac{1}{2} = 0.5 * 100 = 50%
```

### theoretical vs. experimental probability

| | description |
| --- | --- |
| theoretical probability | measures the probability of what SHOULD occur in an experiment |
| experimental probability | measures the probability of what DOES occur in an experiment |

both theoretical and experimental probabilities have the same notation
```math
P(E) = \frac{N(E)}{N(S)}
```

**uniform probability model** - all outcomes are equally likely to occur

### complement equation
the probability of something other than the Event to occur

```math
P(E)’ = 1 – P(E)
```

### compound probability
when two or more events occur

```math
P(A ∩ B) = P(A) ∙ P(B)
```

### addition rule of probability
when either Event A OR B will occur
