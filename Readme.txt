
Amazon is currently underway putting Amazon Lockers across the country. The 
Locker team wants to ensure that lockers are placed so that customers in the 
city are always within a short distance from an Amazon Locker. To account for 
this they need a wat to model locker placements and distances from lockers.

For this task you are provided:
1. A positive whole number range 1-9 representing the length of your city in city blocks.
2. A positive whole number range 1-9 representing the width of your city in city blocks
3. An array containing all X coordinates representing Amazon Locker locations, each X coordinate range 1-9
4. An array containing all Y coordinates representing Amazon Locker locations, each Y coordinate range 1-9

Your job is to construct 2-d grid of the city. Each elemnt of the grid should be
a positive whole number that specifies the number of blocks to the closest locker.
The distance between the two blocks is the sum of their horizontal and vertical
distance (a move in the diagonal direction is therefore considered a distance 
of 2). Return your grid as 2D array of integers where the first index corresponds 
to the X dimension and the second index corresponds to the Y direction.

Example # 1:
Given
1. 3
2. 5
3. [1]
4. [1]

Return
012
123
234
345
456

Example # 2:
Given
1. 5
2. 7
3. [2,4]
4. [3,7]

Return
32345
21234
10123
21234
32323
43212
32101