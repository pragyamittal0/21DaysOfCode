#### Day-23
###### Diagonal traversal

The historic state of Wakanda has various monuments and souveniers which are visited by many travellers every day. The guides follow a prescribed route of visiting the monuments which improves them understand the relevance of each monument. The route of the monument is fixed and expressed in a 2-d matrix where the travellers visit the prescribed next monument. For example
1  2  3
4  5  6
7  8  9
is the prescribed route and the visitors travels this path: 1->2->3->4->5->6->7->8->9
However, a certain visitor decides to travel a different path as follows:
1. The visitor only plans to visit the upper diagonal triangle of the monument list.
2. The visitor travels diagonally till there are no more moves left in the current journey. 
3. He then visits the adjacent monument to the first monument of current diagonal journey. 
4. He continues the same path till all the monuments of the upper half have been travelled.
For Example:
The monuments are named as:
1    2    3    4
5    6    7    8
9   10  11  12
13 14  15  16
The path followed by the visitor is: 1->6->11->16->2->7->12->3->8->4
You are required to print the path followed by the traveller to visit all the monuments.
Refer to the photo for a better clarification.
1. You are given a number n, representing the number of rows and columns of a square matrix.
2. You are given n * n numbers, representing elements of 2d array a.
3. You are required to diagonally traverse the upper half of the matrix and print the contents.
For details check image.

###### Saddle point
1. You are given a square matrix of size 'n'. You are given n*n elements of the square matrix. 
2. You are required to find the saddle price of the given matrix and print the saddle price. 
3. The saddle price is defined as the least price in the row but the maximum price in the column of the matrix.
