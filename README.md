# Loops Exit Ticket

## Instructions for lab submission

1. Fork the assignment repo
1. Clone your Fork to your machine
1. Complete the lab
1. Push your changes to your Fork
1. Submit a Pull Request back to the assignment repo
1. Paste a link to of your Fork on Canvas and submit

## Question 1

What will the code below print?

```swift
var myNum = 8

for number in 4..<8{
    if number == 7 {
        break
    } else {
        myNum += number
    }
}

print(myNum)
```
MyNum initializes at 8 and the loop begins with the range value of 4. So it adds the initial value of myNum which is 8 into the initial range number which is 4. The result is 12. The loop repeats until the range value begins at 7 then the function is halted.

or basically 8+(4) --> 12+(5) --> 17+(6) ->>> 7 HALT

***
## Question 2

Which of the following loops will print out all the numbers between 1 and 100, inclusive?  Select all that apply.

a)
```swift
for i in 1..<100 {
    print(i)
}
```
A. does not apply as the value stops at 99

B)
```swift
for j in 1...100 {
    print(j)
}
```
B. applies because it completes at 100

C)
```swift
for k in 1..<1000 where k < 101 {
    print(k)
}
```
C. applies because k will run until it maxes out before 101 which produces 1-100

D)
```swift
for l in 1...100 where _ < 101 {
    print(l)
}
```
D. does not apply since it runs into a syntax error where _ is not defined.

***
## Question 3

How many times will the code below print **"Nesting!"** ?

```swift
for _ in 1...10{
    for _ in 1...10{
        print("Nesting!")
    }
}
```
"Nesting" will printed 100 times because the master nest will run 10 times and within that next is another next that prints "Nesting" 10 times. 10x10 = 100 times!

***
## Question 4

Which of the loops below will run forever? Select all that apply.

a)
```swift
var q = 0

while q%2 != 1 {
    print("Hello Problem Two!")
    q += 2
}
```
A will run forever

b)
```swift
var r = 0

while r < 10 {
    print("Hi there!")
    r += 11
}
```
B will not run forever

c)
```swift
var s = 0

while 3 != 3 {
    print("Howdy!")
    s += 1
}
```
C will not run forever

d)
```swift
var t = 0

while t == t{
    print("Ahoy-hoy!")
    t += 1
}
```
D will run forever
***
