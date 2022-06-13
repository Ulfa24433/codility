# codility

Write the function:
Func solution (T[] string, R[] string) int

T[i] is string coresponding to the I-th test case name.
R[i] is the result of this test case, containing
One of the four value (wrong answer, OK, runtime error,
Time limit exceeded)

Test case are named according to the following rule:
If the test case is the only test case in the group, 
Its name is [task name] + [group number].
If there's more than one test in the group, the name is
Extended by the lowercase english leter which is
Different for each test case. Example, the test case name are:
Test1, test2a, test2b. In this example, test2a and test2b 
From one group, and test1 from another.

The result should be return is
Number of group passed multiplied by 100 divided by total number 
Of group. Ex: if the program passed two group out of three,
The result is 2*100/3 = 66.6. so the return value is 66.

The program scored point for a group only when
The result of every test case in the group is "ok".

Example:
T[0] = "test1a"   R[0] = "wrong answer"
T[1] = "test2"    R[1] = "OK"
T[2] = "test1b"   R[2] = "runtime error"
T[3] = "test1c"   R[3] = "OK"
T[4] = "test3"    R[4] = "time limit exceeded"

The function should return 33, total of group passed is one (the second group)
For "test1c" is not passed, because another test1-x are not OK
