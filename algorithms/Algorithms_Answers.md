Add your answers to the Algorithms exercises here.

Exercise I.

a) O(n^3)

b) O(n)

c) O(64 * sqrt(n)/2) => O(sqrt(n))

d) O(n * sqrt(n))

e) O(n^3)

f) O(n)

g) O(n)

Exercise II.

a)

def max_diff(a):
    j = a.index(max(a))
    i = a.index(min(a))
    return max([a[j] - min(a[:j]), max(a[i+1:]) - a[i]])

Exercise III.

a) O(n^2)

b) O(log n)