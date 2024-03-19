# CMPS 2200 Reciation 5
## Answers

**Name:**____Tony Shen and Sean Hall_____________________


Place all written answers from `recitation-05.md` here for easier grading.

How do the running times compare to the asymptotic bounds? How does changing the type of input list change the relative performance of these algorithms?





- **1b.**
Quick sort (fixed pivot):
Worst case value for work and span
Work is O(n^2)
Span is O(nlogn)

Quick sort (random pivot):
Expected value for work and span with random pivot:
Work is O(nlogn)
Span is O((logn)^2)

Tim sort:
THe average value fvor work and span with Tim sort
Work is O(nlogn)
Span is O((logn)^2)
However, if we know more about the list, it has a best case work of O(n). 

- **1c.**
Here are our runtimes for each algorithm with different input sizes:
|   n |   qsort-fixed-pivot |   qsort-random-pivot |   tim_sort |
|-----|---------------------|----------------------|------------|
| 100 |               2.528 |                0.575 |      0.005 |
| 200 |               3.778 |                1.043 |      0.006 |
| 300 |               9.759 |                1.694 |      0.028 |
| 400 |              13.793 |                1.602 |      0.009 |
| 504 |              73.727 |                6.291 |      0.018 |
| 666 |             100.207 |                2.588 |      0.013 |
| 911 |             104.492 |                3.356 |      0.015 |
| 888 |             177.240 |                3.778 |      0.087 |
| 711 |              91.890 |                2.828 |      0.013 |
| 626 |             104.376 |                3.744 |      0.021 |
