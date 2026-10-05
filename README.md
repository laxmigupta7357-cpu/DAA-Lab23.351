<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

## School of Engineering and Technology

<br>

<img width="154" height="157" alt="Mody_University_logo" src="https://github.com/user-attachments/assets/11e32514-7869-4f2d-afc9-b45171b58488" />


<br>

# DESIGN ANALYSIS AND ALGORITHM LAB

### LAB RECORD

<br><br>

**Student Name:** Laxmi Gupta
**Enrollment Number:** 240205

<br>

**Faculty Name:** Dr. P. K. Bishnoi

<br><br>

**Mody University of Science and Technology**
**School of Engineering and Technology**
Lakshmangarh, Rajasthan

</div>

---

<div style="page-break-after: always;"></div>

# INDEX

# INDEX

<table style="width:100%; border-collapse:collapse;">
  <tr>
    <th style="width:10%;">S. No.</th>
    <th style="width:65%;">Program</th>
    <th style="width:25%;">Link</th>
  </tr>

  <tr>
    <td>1</td>
    <td>Addition of Two Numbers</td>
    <td><a href="#program-1-addition-of-two-numbers">Program 1</a></td>
  </tr>

  <tr>
    <td>2</td>
    <td>Largest of Three Numbers</td>
    <td><a href="#program-2-largest-of-three-numbers">Program 2</a></td>
  </tr>

  <tr>
    <td>3</td>
    <td>Factorial of a Number</td>
    <td><a href="#program-3-factorial-of-a-number">Program 3</a></td>
  </tr>

  <tr>
    <td>4</td>
    <td>Prime Number Check</td>
    <td><a href="#program-4-prime-number-check">Program 4</a></td>
  </tr>

  <tr>
    <td>5</td>
    <td>Fibonacci Series</td>
    <td><a href="#program-5-fibonacci-series">Program 5</a></td>
  </tr>

  <tr>
    <td>6</td>
    <td>Bubble Sort</td>
    <td><a href="#program-6-bubble-sort">Program 6</a></td>
  </tr>

  <tr>
    <td>7</td>
    <td>Selection Sort</td>
    <td><a href="#program-7-selection-sort">Program 7</a></td>
  </tr>

  <tr>
    <td>8</td>
    <td>Insertion Sort</td>
    <td><a href="#program-8-insertion-sort">Program 8</a></td>
  </tr>

  <tr>
    <td>9</td>
    <td>Merge Sort</td>
    <td><a href="#program-9-merge-sort">Program 9</a></td>
  </tr>

  <tr>
    <td>10</td>
    <td>Quick Sort</td>
    <td><a href="#program-10-quick-sort">Program 10</a></td>
  </tr>
</table>


---

<div style="page-break-after: always;"></div>

# Program 1: Addition of Two Numbers

## Aim

To write a Python program to find the sum of two numbers.

## Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b

print("Sum =", sum)
```

## Sample Output

```text
Enter first number: 10
Enter second number: 20
Sum = 30
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 2: Largest of Three Numbers

## Aim

To write a Python program to find the largest among three numbers.

## Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    largest = a
elif b >= a and b >= c:
    largest = b
else:
    largest = c

print("Largest number =", largest)
```

## Sample Output

```text
Enter first number: 10
Enter second number: 25
Enter third number: 15
Largest number = 25
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 3: Factorial of a Number

## Aim

To write a Python program to calculate the factorial of a given number.

## Program

```python
n = int(input("Enter a number: "))

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print("Factorial =", fact)
```

## Sample Output

```text
Enter a number: 5
Factorial = 120
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 4: Prime Number Check

## Aim

To write a Python program to check whether a given number is prime or not.

## Program

```python
n = int(input("Enter a number: "))

prime = True

if n < 2:
    prime = False
else:
    for i in range(2, n):
        if n % i == 0:
            prime = False
            break

if prime:
    print(n, "is a Prime Number")
else:
    print(n, "is not a Prime Number")
```

## Sample Output

```text
Enter a number: 7
7 is a Prime Number
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 5: Fibonacci Series

## Aim

To write a Python program to generate the Fibonacci series.

## Program

```python
n = int(input("Enter number of terms: "))

a = 0
b = 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

## Sample Output

```text
Enter number of terms: 7
0 1 1 2 3 5 8
```

[Back to Index](#index)

---

# Program 6: Bubble Sort

## Aim

Write a Python program to sort the given array in ascending order using Bubble Sort. Also calculate its execution time and memory usage.

## Program

```python
import time
import tracemalloc

arr = [50, 30, 10, 40, 20]

# Start memory
tracemalloc.start()

# Start time
start = time.time()

# Bubble Sort
n = len(arr)

for i in range(n):
    for j in range(n - i - 1):

        if arr[j] > arr[j + 1]:
            temp = arr[j]
            arr[j] = arr[j + 1]
            arr[j + 1] = temp

# End time
end = time.time()

# Memory
current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")
```

## Sample Output

<img width="270" height="45" alt="image" src="https://github.com/user-attachments/assets/0f51adf1-12a8-449b-95c1-5d14dbe39753" />


[Back to Index](#index)

---

# Program 7: Selection Sort

## Aim

Write a Python program to sort an array using Selection Sort and find its execution time and memory used.

## Program

```python
import time
import tracemalloc

arr = [50, 30, 10, 40, 20]

tracemalloc.start()

start = time.time()

# Selection Sort
n = len(arr)

for i in range(n):

    small = i

    for j in range(i + 1, n):

        if arr[j] < arr[small]:
            small = j

    temp = arr[i]
    arr[i] = arr[small]
    arr[small] = temp

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")
```

## Sample Output

<img width="288" height="59" alt="image" src="https://github.com/user-attachments/assets/87ce28e4-1a9b-41dc-a528-ecbc388a0628" />


[Back to Index](#index)

---

# Program 8: Insertion Sort

## Aim

Write a Python program to sort an array using Insertion Sort and find its execution time and memory used.

## Program

```python
import time
import tracemalloc

arr = [50, 30, 10, 40, 20]

tracemalloc.start()

start = time.time()

# Insertion Sort
n = len(arr)

for i in range(1, n):

    key = arr[i]
    j = i - 1

    while j >= 0 and arr[j] > key:

        arr[j + 1] = arr[j]
        j = j - 1

    arr[j + 1] = key

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")
```

## Sample Output

<img width="293" height="55" alt="image" src="https://github.com/user-attachments/assets/1481a177-cb08-4f15-a0ea-fb037ccfce50" />


[Back to Index](#index)

---

# Program 9: Merge Sort

## Aim

Write a Python program to sort an array using Merge Sort and find its execution time and memory used.

## Program

```python
import time
import tracemalloc

def merge_sort(arr):

    if len(arr) <= 1:
        return arr

    mid = len(arr) // 2

    left = merge_sort(arr[:mid])
    right = merge_sort(arr[mid:])

    result = []

    i = 0
    j = 0

    while i < len(left) and j < len(right):

        if left[i] < right[j]:
            result.append(left[i])
            i = i + 1

        else:
            result.append(right[j])
            j = j + 1

    result.extend(left[i:])
    result.extend(right[j:])

    return result


arr = [50, 30, 10, 40, 20]

tracemalloc.start()

start = time.time()

arr = merge_sort(arr)

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```

## Sample Output

<img width="340" height="62" alt="image" src="https://github.com/user-attachments/assets/415dafbb-38f3-415a-9898-2ddb100174f5" />


[Back to Index](#index)

---
# Program 10: Quick Sort

## Aim

Write a Python program to sort an array using Quick Sort and find its execution time and memory used.

## Program

```python
import time
import tracemalloc

def quick_sort(arr):

    if len(arr) <= 1:
        return arr

    pivot = arr[0]

    left = []
    right = []

    for i in range(1, len(arr)):

        if arr[i] < pivot:
            left.append(arr[i])
        else:
            right.append(arr[i])

    return quick_sort(left) + [pivot] + quick_sort(right)


arr = [50, 30, 10, 40, 20]

tracemalloc.start()

start = time.time()

arr = quick_sort(arr)

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```

## Sample Output

<img width="299" height="50" alt="image" src="https://github.com/user-attachments/assets/315c8f0d-3984-4b8b-ab23-2f77268a8890" />

[Back to Index](#index)

---





