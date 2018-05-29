# Magic-Points
Magic Points
Given an integer , we say a point  on a 2D plane is a magic point, if and only if both  and  are integers, and exactly one of the following conditions is satisfied:

 and ;

 and ;

 and ;

 and .

It's easy to discover that there are  magic points in total. These magic points are numbered from  to  in counter-clockwise order starting from .

DreamGrid can create  magic lines from these magic points. Each magic line passes through exactly two magic points but cannot be parallel to the line  or  (that is to say, the coordinate axes).

The intersections of the magic lines are called dream points, and for some reason, DreamGrid would like to make as many dream points as possible. Can you tell him how to create these magic lines?

Input

There are multiple test cases. The first line of input contains an integer  (about 100), indicating the number of test cases. For each test case, there is only one integer  ().

Output

For each case output  integers  in one line separated by one space, indicating that in your answer, point  and point  is connected by a line for all .

If there are multiple answers, you can print any of them.

Sample Input

3
2
3
4
Sample Output

0 2 1 3
1 4 2 5 3 6
0 6 1 9 3 8 4 10
Hint


