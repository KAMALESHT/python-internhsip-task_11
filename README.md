# python-internhsip-task_11


1.Write a program using zip() function and list() function, create a merged list of tuples from the two lists given.

solution:

list_1=['A','B','C','D','E']

list_2=[1,2,3,4,5]

zipped_list=list(zip(list_1,list_2))

print(zipped_list)

2.First create a range from 1 to 8. Then using zip, merge the given list and the range together to create a new list of tuples

solution:

range_1= [x for x in range(1,8)]

list_1=['A','B','C','D','E','F','G']

result=list(zip(range_1,list_1))

print(result)

3.Using sorted() function, sort the list in ascending order.

solution:

list_1=[2,4,6,5,3,7,1,8,0,9]

print(sorted(list_1))

4.Write a program using filter function, filter the even numbers so that only odd numbers are passed to the new list.

solution:

list_1=[2,4,6,5,3,7,1,8,0,9]

odd=list(filter(lambda x: x%2!=0,list_1))

print(odd)
