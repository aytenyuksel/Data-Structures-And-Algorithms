# Binary Search Tree

Binary search tree is a node-based tree data structure for using the organizing datas.
BST start with the pivot namber who called "root".
It is posibble to every number can be pivot.

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

In this series, if we select number 7 as a pivot, it will be root because it being first choosen.

We are writing the number 7 on the top;

                                       [7]
                                    
If the next number is small than he 7 it will be left side otherwise it will be right side of the 7;

                                       [7]
                                 [1]         [5]

Keep adding the numbers on the following this order.

                                          [7]
                                   [1]          [5]
                               [0]     [3]           [8]
                                    [2]   [4]     [6]   [9]
                                    
