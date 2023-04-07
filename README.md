# 1_custom_range_lab_iterators_and_generators
Create a class called custom_range that receives a start (int) and an   (int) upon initialization. Implement the __iter__ and __next__ methods, so the iterator returns the numbers from the start to the end (inclusive).

Test Code
one_to_ten = custom_range(1, 10)
for num in one_to_ten:
    print(num)
    
    
Output
1
2
3
4
5
6
7
8
9
10

