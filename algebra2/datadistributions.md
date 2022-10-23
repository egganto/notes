# data distributions

## measures of center and spread

### mean
- the **mean** of a data is its average
- is found by summing all values and then dividing by the total

### median
- the middle number, or the average of the middle two numbers in a data set
- if the data set has an even number of values, the median is the average of the mid two #s
- if the data set has an odd number of values, the median is the number in the middle of the set

### standard deviation
- the average distance of any data value from the mean

```math
\sigma = \sqrt{\frac{1}{k}\sum_{n=1}^k(n_n-x)^2}
```

k = total number of data values
x<sub>n</sub> = each data value

| calculating standard deviation |
| --- |
| **step 1**: compute the mean (x) of the data set |
| **step 2**: subtract x from each data value, then square the result |
| - if data values are repeated, you must subtract the mean from each one |
| **step 3**: sum the numbers you calculated in **step 2**. then divide by the number of values, getting a new mean |
| **step 4**: take the square root of new mean, this is the value of the standard deviation |

### five-number summary
- a set of descriptive statistics that can tell you about how the data in a set are spread out

the five numbers in the summary
  - the minimum data value
	- the median of the lower quartile (Q1)
	- the median of the entire data set (Q2)
	- the median of the upper quartile (Q3)
	- the maximum data value

- the min val in the data set is the smallest number
  the max data val is the largest number
- the median of the lower quartile is the median of the lower half of the data (Q1)
  if the lower quartile has an even number of data points, then Q1 would be the average of the middle two points
- the median of the upper quartile is the median of the upper half of the data (Q3)
  if the upper quartile has an even number of data points, then Q3 would be the average of the middle two points
- once you find the values of Q3 and Q1, you can subtract the two to find the interquartile range (IQR)
  this value can be used to measure spread

```math
Q3-Q1=\,spread
```
