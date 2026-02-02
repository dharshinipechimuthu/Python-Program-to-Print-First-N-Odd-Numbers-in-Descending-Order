# Python-Program-to-Print-First-N-Odd-Numbers-in-Descending-Order

n = int(input("Enter the limit: "))

if n % 2 == 0:
    n = n - 1

for i in range(n, 0, -2):
    print(i)

Output:
Enter the limit: 10
9
7
5
3
1
