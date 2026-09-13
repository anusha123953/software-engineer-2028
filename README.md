numbers  = [10, 20, 30, 40, 50]
print(numbers[0])
print(numbers[1])
print(numbers[2])

fruits = ["apple", "banana", "mango"]
fruits.append("orange")
fruits.insert(1, "grape")
print(fruits)

numbers = [10, 20, 30, 40]
numbers.remove(30)
print(numbers)

numbers = [10, 20, 30, 40, 50]
numbers.pop(1)
print(numbers)

numbers = [0, 1, 2, 3, 4, 5, 6]
print(numbers[1:5])

numbers = [0, 1, 2, 3, 4, 5, 6]
print(numbers[::2])

matrix = [
    [10, 20, 30],
    [40, 50, 60],
    [70, 80, 90]
]

print(matrix[2][1])

numbers = [5, 10, 15, 20, 25]
numbers.append(30)
numbers.pop(2)
print(numbers)

fruits = ["apple", "banana", "mango", "orange"]
fruits[1] = "grape"
fruits.remove("mango")
print(fruits)

numbers = [10, 20, 30,40, 50, 60]
print(numbers[1:5:2])

numbers = [1, 2,3,4,5]
print(numbers[-1])
print(numbers[-3])
print(numbers[::-1])

data = [
    [10, 20],
    [30, 40],
    [50, 60]
]

print(data[1][0])
print(data[2][1])
C:\Users\Anusha\PyCharmMiscProject\.venv\Scripts\python.exe C:\Users\Anusha\PyCharmMiscProject\.py 
10
20
30
['apple', 'grape', 'banana', 'mango', 'orange']
[10, 20, 40]
[10, 30, 40, 50]
[1, 2, 3, 4]
[0, 2, 4, 6]
80
[5, 10, 20, 25, 30]
['apple', 'grape', 'orange']
[20, 40]
5
3
[5, 4, 3, 2, 1]
30
60
