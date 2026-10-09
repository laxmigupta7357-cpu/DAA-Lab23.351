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

  <tr>
    <td>11</td>
    <td>Time and Memory Comparison of all Sortings</td>
    <td><a href="#program-11-Time-and-Memory-Comparison-of-all-Sortings">Program 11</a></td>
  </tr>

  <tr>
    <td>12</td>
    <td>Linear Search</td>
    <td><a href="#program-12-linear-search">Program 12</a></td>
  </tr>

  <tr>
    <td>13</td>
    <td>Binary Search</td>
    <td><a href="#program-13-binary-search">Program 13</a></td>
  </tr>
  
  <tr>
    <td>14</td>
    <td>Time and Memory Comparison of linear and binary searching</td>
    <td><a href="#program-14-Time-and-Memory-Comparison-of-linear-and-binary-searching">Program 14</a></td>
  </tr>

  <tr>
    <td>15</td>
    <td>Time and Memory Comparison of different time complexities</td>
    <td><a href="#program-15-Time-and-Memory-Comparison-of-different-time-complexities">Program 15</a></td>
  </tr>

  <tr>
    <td>16</td>
    <td>Undirected Graph</td>
    <td><a href="#program-16-Undirected-Graph">Program 16</a></td>
  </tr>

  <tr>
    <td>17</td>
    <td>Directed Graph</td>
    <td><a href="#program-17-Directed-Graph">Program 17</a></td>
  </tr>

  <tr>
    <td>18</td>
    <td>Weighted Graph</td>
    <td><a href="#program-18-Weighted-Graph">Program 18</a></td>
  </tr>

  <tr>
    <td>19</td>
    <td>Directed and Weighted Graph</td>
    <td><a href="#program-19-Directed-and-Weighted-Graph">Program 19</a></td>
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
# Program 11: Time and Memory Comparison of all Sortings

## Aim

Implement Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort in Python. Calculate the execution time and memory usage of each algorithm and compare their performance using graphs.

## Program

```python
import time
import matplotlib.pyplot as plt

# Original array
arr = [50, 30, 10, 40, 20, 70, 60, 80, 90, 100]


# ---------------- BUBBLE SORT ----------------

def bubble_sort(a):

    a = a.copy()

    n = len(a)

    for i in range(n):
        for j in range(n - i - 1):

            if a[j] > a[j + 1]:

                temp = a[j]
                a[j] = a[j + 1]
                a[j + 1] = temp

    return a


# ---------------- SELECTION SORT ----------------

def selection_sort(a):

    a = a.copy()

    n = len(a)

    for i in range(n):

        small = i

        for j in range(i + 1, n):

            if a[j] < a[small]:
                small = j

        temp = a[i]
        a[i] = a[small]
        a[small] = temp

    return a


# ---------------- INSERTION SORT ----------------

def insertion_sort(a):

    a = a.copy()

    n = len(a)

    for i in range(1, n):

        key = a[i]
        j = i - 1

        while j >= 0 and a[j] > key:

            a[j + 1] = a[j]
            j = j - 1

        a[j + 1] = key

    return a


# ---------------- MERGE SORT ----------------

def merge_sort(a):

    if len(a) <= 1:
        return a

    mid = len(a) // 2

    left = merge_sort(a[:mid])
    right = merge_sort(a[mid:])

    result = []

    i = 0
    j = 0

    while i < len(left) and j < len(right):

        if left[i] < right[j]:
            result.append(left[i])
            i += 1
        else:
            result.append(right[j])
            j += 1

    result.extend(left[i:])
    result.extend(right[j:])

    return result


# ---------------- QUICK SORT ----------------

def quick_sort(a):

    if len(a) <= 1:
        return a

    pivot = a[0]

    left = []
    right = []

    for i in range(1, len(a)):

        if a[i] < pivot:
            left.append(a[i])
        else:
            right.append(a[i])

    return quick_sort(left) + [pivot] + quick_sort(right)


# ---------------- FIND EXECUTION TIME ----------------

times = []

start = time.time()
bubble_sort(arr)
times.append(time.time() - start)

start = time.time()
selection_sort(arr)
times.append(time.time() - start)

start = time.time()
insertion_sort(arr)
times.append(time.time() - start)

start = time.time()
merge_sort(arr)
times.append(time.time() - start)

start = time.time()
quick_sort(arr)
times.append(time.time() - start)


# ---------------- PRINT TIME ----------------

print("Bubble Sort Time:", times[0])
print("Selection Sort Time:", times[1])
print("Insertion Sort Time:", times[2])
print("Merge Sort Time:", times[3])
print("Quick Sort Time:", times[4])


# ---------------- GRAPH ----------------

names = [
    "Bubble Sort",
    "Selection Sort",
    "Insertion Sort",
    "Merge Sort",
    "Quick Sort"
]

plt.bar(names, times)

plt.xlabel("Sorting Algorithms")
plt.ylabel("Execution Time")

plt.title("Comparison of Sorting Algorithms")

plt.xticks(rotation=20)

plt.grid()

plt.show()

```

## Sample Output

<img width="311" height="53" alt="image" src="https://github.com/user-attachments/assets/f7f8fca7-2761-4e76-9c39-664cae37f09a" />
<img width="911" height="459" alt="image" src="https://github.com/user-attachments/assets/c0889196-962d-429a-817d-57d0bef9a7b5" />

[Back to Index](#index)

---
# Program 12: Linear Search

## Aim

Write a Python program to search for a given element in an array using Linear Search. Also calculate its execution time and memory usage.

## Program

```python
import time
import tracemalloc

arr = [10, 20, 30, 40, 50]
value = 30

tracemalloc.start()

start = time.time()

found = False

for i in range(len(arr)):
    if arr[i] == value:
        print("Element found at position:", i)
        found = True
        break

if found == False:
    print("Element not found")

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```

## Sample Output

<img width="293" height="56" alt="image" src="https://github.com/user-attachments/assets/97729835-b4cd-4c75-8e4e-129e0f99c13e" />

[Back to Index](#index)

---
# Program 13: Binary Search

## Aim

Write a Python program to search for a given element in a sorted array using Binary Search. Also calculate its execution time and memory usage.

## Program

```python
import time
import tracemalloc

arr = [10, 20, 30, 40, 50]
value = 40

tracemalloc.start()

start = time.time()

low = 0
high = len(arr) - 1
found = False

while low <= high:

    mid = (low + high) // 2

    if arr[mid] == value:
        print("Element found at position:", mid)
        found = True
        break

    elif arr[mid] < value:
        low = mid + 1

    else:
        high = mid - 1

if found == False:
    print("Element not found")

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```

## Sample Output

<img width="289" height="62" alt="image" src="https://github.com/user-attachments/assets/b1d80fb8-9198-4293-9c64-0b81cebb656a" />

[Back to Index](#index)

---
# Program 14: Time and Memory Comparison of linear and binary searching

## Aim

Write a Python program to compare the execution time of Linear Search and Binary Search and represent the comparison using a graph.

## Program

```python
import time
import matplotlib.pyplot as plt

# Different input sizes
sizes = [1000, 5000, 10000, 20000, 50000]

linear_times = []
binary_times = []

for n in sizes:

    arr = list(range(n))
    value = n - 1

    # ---------------- Linear Search ----------------

    start = time.perf_counter()

    for i in range(len(arr)):
        if arr[i] == value:
            break

    end = time.perf_counter()

    linear_times.append(end - start)


    # ---------------- Binary Search ----------------

    start = time.perf_counter()

    low = 0
    high = len(arr) - 1

    while low <= high:

        mid = (low + high) // 2

        if arr[mid] == value:
            break

        elif arr[mid] < value:
            low = mid + 1

        else:
            high = mid - 1

    end = time.perf_counter()

    binary_times.append(end - start)


# Print results
print("Input Size        Linear Search                      Binary Search")

for i in range(len(sizes)):
    print(
        sizes[i],
        "        ",
        linear_times[i],
        "        ",
        binary_times[i]
    )


# ---------------- GRAPH ----------------

plt.plot(
    sizes,
    linear_times,
    marker='o',
    label="Linear Search"
)

plt.plot(
    sizes,
    binary_times,
    marker='o',
    label="Binary Search"
)

plt.xlabel("Input Size (n)")
plt.ylabel("Execution Time (seconds)")

plt.title("Linear Search vs Binary Search")

plt.legend()
plt.grid()

plt.show()

```

## Sample Output

<img width="408" height="87" alt="image" src="https://github.com/user-attachments/assets/46db1611-d130-415e-beac-b101988b351c" />
<img width="479" height="355" alt="image" src="https://github.com/user-attachments/assets/0a74dcb3-82bd-426f-9118-4007ab780cf5" />



[Back to Index](#index)

---

# Program 15: Time and Memory Comparison of different time complexities

## Aim

Write a Python program to demonstrate different time complexities and calculate execution time and memory usage.

## Program

```python
# ============================================================

# ------------------------------------------------------------
# 1. O(1) - Constant Time
# ------------------------------------------------------------
print("\n========== O(1) - CONSTANT TIME ==========")

a = [10, 20, 30]
print("Array:", a)
print("First element:", a[0])


# ------------------------------------------------------------
# 2. O(log n) - Logarithmic Time
# ------------------------------------------------------------
print("\n========== O(log n) - LOGARITHMIC TIME ==========")

n = 16
original_n = n

while n > 1:
    n = n // 2

print("Original n:", original_n)
print("Value after repeated division:", n)


# ------------------------------------------------------------
# 3. O(sqrt(n)) - Square Root Time
# ------------------------------------------------------------
print("\n========== O(sqrt(n)) - SQUARE ROOT TIME ==========")

n = 10
i = 1

while i * i <= n:
    i += 1

print("n =", n)
print("Number of iterations:", i - 1)


# ------------------------------------------------------------
# 4. O(n) - Linear Time
# ------------------------------------------------------------
print("\n========== O(n) - LINEAR TIME ==========")

n = 5

for i in range(n):
    print("i =", i)


# ------------------------------------------------------------
# 5. O(n log n) - Linearithmic Time
# ------------------------------------------------------------
print("\n========== O(n log n) - LINEARITHMIC TIME ==========")

n = 4

for i in range(n):
    j = i

    while j > 1:
        j = j // 2

    print("i =", i, "final j =", j)


# ------------------------------------------------------------
# 6. O(n^2) - Quadratic Time
# ------------------------------------------------------------
print("\n========== O(n^2) - QUADRATIC TIME ==========")

n = 2

for i in range(n):
    for j in range(n):
        print("(", i, ",", j, ")")


# ------------------------------------------------------------
# 7. O(n^3) - Cubic Time
# ------------------------------------------------------------
print("\n========== O(n^3) - CUBIC TIME ==========")

n = 2

for i in range(n):
    for j in range(n):
        for k in range(n):
            print("(", i, ",", j, ",", k, ")")


# ------------------------------------------------------------
# 8. O(2^n) - Exponential Time
# ------------------------------------------------------------
print("\n========== O(2^n) - EXPONENTIAL TIME ==========")

def fun_exponential(n):

    if n == 0:
        return

    print(n)

    fun_exponential(n - 1)
    fun_exponential(n - 1)


print("Output for n = 3:")
fun_exponential(3)


# ------------------------------------------------------------
# 9. O(n!) - Factorial Time
# ------------------------------------------------------------
print("\n========== O(n!) - FACTORIAL TIME ==========")

from itertools import permutations

n = 2

for p in permutations(range(n)):
    print(p)


# ------------------------------------------------------------
# 10. EXECUTION TIME
# ------------------------------------------------------------
print("\n========== EXECUTION TIME ==========")

import time

start = time.time()

# Program
for i in range(1000000):
    pass

end = time.time()

print("Execution Time:", end - start, "seconds")


# ------------------------------------------------------------
# 11. MEMORY USED
# ------------------------------------------------------------
print("\n========== MEMORY USED ==========")

import tracemalloc

tracemalloc.start()

# Program
a = [i for i in range(100000)]

current, peak = tracemalloc.get_traced_memory()

print("Current Memory:", current, "bytes")
print("Peak Memory:", peak, "bytes")

tracemalloc.stop()


# ------------------------------------------------------------
# END
# ------------------------------------------------------------
print("\n==============================================")
print("       ALL COMPLEXITIES EXECUTED SUCCESSFULLY")
print("==============================================")
# ------------------------------------------------------------
# 12. GRAPH PLOT - COMPARISON OF TIME COMPLEXITIES
# ------------------------------------------------------------

import matplotlib.pyplot as plt

# Values of n
n_values = range(1, 11)

# Different time complexities
O_1 = [1 for n in n_values]
O_log_n = [__import__('math').log2(n) for n in n_values]
O_sqrt_n = [n ** 0.5 for n in n_values]
O_n = [n for n in n_values]
O_n_log_n = [n * __import__('math').log2(n) for n in n_values]
O_n2 = [n ** 2 for n in n_values]
O_n3 = [n ** 3 for n in n_values]
O_2n = [2 ** n for n in n_values]

# Plot
plt.figure(figsize=(10, 6))

plt.plot(n_values, O_1, marker='o', label='O(1)')
plt.plot(n_values, O_log_n, marker='o', label='O(log n)')
plt.plot(n_values, O_sqrt_n, marker='o', label='O(sqrt(n))')
plt.plot(n_values, O_n, marker='o', label='O(n)')
plt.plot(n_values, O_n_log_n, marker='o', label='O(n log n)')
plt.plot(n_values, O_n2, marker='o', label='O(n^2)')
plt.plot(n_values, O_n3, marker='o', label='O(n^3)')
plt.plot(n_values, O_2n, marker='o', label='O(2^n)')

plt.xlabel("Input Size (n)")
plt.ylabel("Number of Operations / Growth")
plt.title("Comparison of Time Complexities")

plt.legend()
plt.grid(True)

plt.show()

```

## Sample Output

```text
========== O(1) - CONSTANT TIME ==========
Array: [10, 20, 30]
First element: 10

========== O(log n) - LOGARITHMIC TIME ==========
Original n: 16
Value after repeated division: 1

========== O(sqrt(n)) - SQUARE ROOT TIME ==========
n = 10
Number of iterations: 3

========== O(n) - LINEAR TIME ==========
i = 0
i = 1
i = 2
i = 3
i = 4

========== O(n log n) - LINEARITHMIC TIME ==========
i = 0 final j = 0
i = 1 final j = 1
i = 2 final j = 1
i = 3 final j = 1

========== O(n^2) - QUADRATIC TIME ==========
( 0 , 0 )
( 0 , 1 )
( 1 , 0 )
( 1 , 1 )

========== O(n^3) - CUBIC TIME ==========
( 0 , 0 , 0 )
( 0 , 0 , 1 )
( 0 , 1 , 0 )
( 0 , 1 , 1 )
( 1 , 0 , 0 )
( 1 , 0 , 1 )
( 1 , 1 , 0 )
( 1 , 1 , 1 )

========== O(2^n) - EXPONENTIAL TIME ==========
Output for n = 3:
3
2
1
1
2
1
1

========== O(n!) - FACTORIAL TIME ==========
(0, 1)
(1, 0)

========== EXECUTION TIME ==========
Execution Time: 0.09830784797668457 seconds

========== MEMORY USED ==========
Current Memory: 3993016 bytes
Peak Memory: 3993048 bytes

==============================================
       ALL COMPLEXITIES EXECUTED SUCCESSFULLY
==============================================

```
<img width="926" height="449" alt="image" src="https://github.com/user-attachments/assets/cccdedfc-0dc8-4ef6-8d7d-6dadf1b48c63" />


[Back to Index](#index)

---
# Program 16: Undirected Graph

## Aim

Write a Python program to create and represent an Undirected Graph using a Node and Graph class.

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)
        node2.neighbors.append(node1)

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor in node.neighbors:
                print(neighbor.data, end=" ")
            print()


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add edges
graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)
graph.add_edge(D, E)
graph.add_edge(E, A)

# Print graph
print("Undirected Graph:")
graph.print_graph()

```

## Sample Output

```text
Undirected Graph:
A -> B C E 
B -> A D 
C -> A D 
D -> B C E 
E -> D A 
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 17: Directed Graph

## Aim

Write a Python program to create and represent a Directed Graph using a Node and Graph class.

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor in node.neighbors:
                print(neighbor.data, end=" ")
            print()


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add directed edges
graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)
graph.add_edge(D, E)
graph.add_edge(E, A)

# Print graph
print("Directed Graph:")
graph.print_graph()

```

## Sample Output

```text
Directed Graph:
A -> B C 
B -> D 
C -> D 
D -> E 
E -> A 
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 18: Weighted Graph

## Aim

Write a Python program to create and represent a Weighted Graph using a Node and Graph class.

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))
        node2.neighbors.append((node1, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor, weight in node.neighbors:
                print(neighbor.data, "(", weight, ")", end=" ")
            print()


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add weighted edges
graph.add_edge(A, B, 5)
graph.add_edge(A, C, 3)
graph.add_edge(B, D, 2)
graph.add_edge(C, D, 4)
graph.add_edge(D, E, 6)
graph.add_edge(E, A, 7)

# Print graph
print("Weighted Graph:")
graph.print_graph()

```

## Sample Output

```text
Weighted Graph:
A -> B ( 5 ) C ( 3 ) E ( 7 ) 
B -> A ( 5 ) D ( 2 ) 
C -> A ( 3 ) D ( 4 ) 
D -> B ( 2 ) C ( 4 ) E ( 6 ) 
E -> D ( 6 ) A ( 7 ) 
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 19: Directed and Weighted Graph

## Aim

Write a Python program to create and represent a Directed and Weighted Graph using a Node and Graph class.

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor, weight in node.neighbors:
                print(neighbor.data, "(", weight, ")", end=" ")
            print()


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add directed and weighted edges
graph.add_edge(A, B, 5)
graph.add_edge(A, C, 3)
graph.add_edge(B, D, 2)
graph.add_edge(C, D, 4)
graph.add_edge(D, E, 6)
graph.add_edge(E, A, 7)

# Print graph
print("Directed and Weighted Graph:")
graph.print_graph()

```

## Sample Output

```text
Directed and Weighted Graph:
A -> B ( 5 ) C ( 3 ) 
B -> D ( 2 ) 
C -> D ( 4 ) 
D -> E ( 6 ) 
E -> A ( 7 ) 
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>







