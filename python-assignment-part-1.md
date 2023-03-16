
Q1. Why do we call Python as a general purpose and high-level programming language?
```bash
ans= python is a general ppurpose language means it can be used to create different type of programs not to solve only specific problems, and it
is a high level language because it is easily human understandable.
```

Q2. Why is Python called a dynamically typed language?
```bash
ans=python is dynamically typed language because when we create the variable or object its type is decided at the runtime.
```

Q3. List some pros and cons of Python programming language?
```bash
ans: pros:
It is easy to use, large community support,large library support , faster development
cons:
High memory consumtion,notfeasible for mobile enviroment
```

Q4. In what all domains can we use Python?
```bash
ans=Data science , Machine Learning , computer vision , from game development to web development.
```
Q5. What are variable and how can we declare them?
```bash
a variable is nothing but a memory address which store the data.
s="hello"
we can define variable by starting its name from alphabet or an underscore.
```

Q6. How can we take an input from the user in Python?
```bash
ans = by using input() function
ex: name = input("enter your name")
```
Q7. What is the default datatype of the value that has been taken as an input using input() function?
```bash
ans = str
```
Q8. What is type casting?
```bash
type casting means changing the data type of the variable.
```
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
```bash
ans =yes
ex for int values here
a,b = int(input()),int(input())
```
Q10. What are keywords?
```bash
ans=keywords are the predefined words wich has special meaning and those keywords can not be used as the variable name because its value can not be changed.
```
Q11. Can we use keywords as a variable? Support your answer with reason.
```bash
ans=keywords are the predefined words wich has special meaning and those keywords can not be used as the variable name because its value can not be changed.
```

Q12. What is indentation? What's the use of indentaion in Python?
```bash
ans=It is a way of telling a interpreter that the group of statements belongs to a particular block of code and also tells it scope.
```
Q13. How can we throw some output in Python?
```bash
ans = using print() function.
```
Q14. What are operators in Python?
```bash
ans= '+' , '-', '*','%','is','in','not in','/'.
```

Q15. What is difference between / and // operators?
```bash
ans=
'/' it is a binary operator this gives floating point value.
'//' it is gives output values as integer
```


Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
```bash
ans=
x = "iNeuron"
x*4
output:iNeuroniNeuroniNeuroniNeuron
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
```bash
num = int(input())
if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

Q18. What are boolean operator?
```bash
Ans= Boolean operators are those operators whose results value depends on some some condition and can like "<,=<,>=,>!,or,and"etc
```

Q19. What will the output of the following?
1 or 0

0 and 0

True and False and True

1 or 0 or 0

```bash
ans = 
1
0
False
1
```


Q20. What are conditional statements in Python?
```bash 
Ans= The conditional statements are the statements which is used to handle the condition in the program.these statement helps in making decision based on some conditions.
Example:- if , if-else,elif
```


Q21. What is use of 'if', 'elif' and 'else' keywords?
```bash
if = "if"  is used to check a condition.
else ="else" if the if statement does not run than else runs.
elif = if we want to check multiple condition than we can use elif
```

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
```bash
Ans
age = int(input())
if age >= 18:
    print(" I can vote")
else:
    print("I can't vote")
```




Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

```bash
Ans

numbers = [12, 75, 150, 180, 145, 525, 50]

s = 0
for i in numbers:
    if i%2 == 0:
        s+=i
    else:
        pass
print(s)
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
```bash
Ans

n1,n2,n3 = int(input()),int(input()),int(input())
if n1 > n2 and n1 >n3:
    print("Greator=",n1)
elif n2 > n1 and n2 > n3:
    print("Greator=",n2)
else:
    print("Greator=",n3)
```


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```



```bash
ans

numbers = [12, 75, 150, 180, 145, 525, 50]


for i in range(len(numbers)):
    if numbers[i] % 5 == 0 and numbers[i] < 150:
        print(numbers[i])
    elif numbers[i] > 500:
        break
   
```








































