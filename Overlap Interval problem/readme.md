# Overlap Interval problem tips

Overlap problem got the interval like [0,1],[3,5],[2,4],....

## Steps
1. Sort the array by one side (left or right).
2. Cache the first end of interval as target
3. Go through all the intervals. If the interval is exceed the target, record it as the question ask(like add one to count or record the right sides). And replace the target as now interval's right side.