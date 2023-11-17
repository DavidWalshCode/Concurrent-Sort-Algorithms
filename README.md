# Concurrent Sort Algorithms
Different implementations of concurrent sorting algorithms in Go for CS4207 Advanced Programming Concepts &amp; Practices

Compare the execution time of these algorithms and display them

*Rules:*

1. The algorithm must read in a csv called "numbers.csv” which will be generated by the committee and used during the running of the algorithm.

2. The data set used will be an array of 100,000 randomly generated integers in a range of -99,999 to 99,999.

3. Each algorithm will be running the exact same dataset of random ints.

4. ANY form of increasing safety and liveness may be used e.g channels, wait groups, etc.

5. Each algorithm will run three times on the device, with the best time being your final time.

6. The algorithm must be safe or you will be disqualified.

7. The output array must be stored in a csv titled “out(studentnumber).csv”.
