# [16,21,11,8,12,22] 
## Define Merge Sort Steps




                [16,21,11,8,12,22]            - Find the middle of array
                
               [16,21,11] [8,12,22]           - Devide the array 2 parts 
              
            [16] [21,11]   [8,12] [22]        - Devide the array 2 parts again
           
         [16] [21] [11]     [8] [12] [22]     - Break every element to single parts
				
            [16] [11,21]   [8,12] [22]        - Sort the element smallest to largest group by 2
           
               [11,16,21] [8,12,22]           - Merge divided groups and sort the elements in the gruop
            
                [8,11,12,16,21,22]            - Merge final groups and sort smallest to largest
								
								
## Find Big O

In first 2 step we are breaking the array or arrays 2 parts and after than we combine the arrays group by group.

2^x = n
x = logn

								Big O = O(logn)


      
