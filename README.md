# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program

a) do...while 

```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()

```

## Output

<img width="913" height="176" alt="do while" src="https://github.com/user-attachments/assets/3533b253-d2aa-4789-8c0a-8de04316577d" />

b) while...do

```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")

```
## output

<img width="1054" height="158" alt="while do" src="https://github.com/user-attachments/assets/bc4684a3-13de-4351-aef1-87bf0bd724eb" />

c) if...else

```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()

```
## output

<img width="1029" height="99" alt="if else" src="https://github.com/user-attachments/assets/4f0779d1-c2a2-4970-b5de-78ea43031e6e" />

d) switch 

```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()

```

## output

<img width="944" height="112" alt="switch" src="https://github.com/user-attachments/assets/909993b7-14a6-4c02-87cc-61eeb1c3134e" />

e) for

```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()

```

## output

<img width="963" height="99" alt="for" src="https://github.com/user-attachments/assets/614beff5-998b-4dca-ae4c-8bf9d96840f6" />

## Result

Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


