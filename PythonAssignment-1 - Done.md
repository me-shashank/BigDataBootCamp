## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans. We call it a general purpose programming language as it can be used for various different purposes, and high-level because the syntax involved is human readable.

Q2. Why is Python called a dynamically typed language?
Ans. It is called so, because type of variable is determined only at the runtime.

Q3. List some pros and cons of Python programming language?
Ans. 
Pros : Beginner-friendly, Large Community, Extensive Libraries, Highly Scalable.
Cons : Security, Slower than compiled languages, Work Environment, Dynamically-typed language.

Q4. In what all domains can we use Python?
Ans. ML/AI, Web development, Game development, Mobile app development, Desktop GUI etc.

Q5. What are variable and how can we declare them?
Ans. Variable are nothing but name given to memory location. We cannot declare variable in python, rather we create and assign some values so declare and defination both at same time.

Q6. How can we take an input from the user in Python?
Ans. Using input(), eg. a = input('Enter the value for a: ')

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans. String

Q8. What is type casting?
Ans. Changing the datatype of a variable to some other type.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans. Yes, eg. a,b,c = input('Enter three values a, b, c: ').split()

Q10. What are keywords?
Ans. Keywords are Special reserved words that have specific meanings and purposes.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans. No we cannot, as the keyword has specific purpose using it variable will throw an error.

Q12. What is indentation? What's the use of indentaion in Python?
Ans. Indentation refers to the spaces at the beginning of a code line. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Ans. Using print() function.

Q14. What are operators in Python?
Ans. Operators are special symbols in Python that carry out arithmetic or logical computations.

Q15. What is difference between / and // operators?
Ans. / - Floating division. // - Integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans. print("iNeuroniNeuroniNeuroniNeuron")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans.
``` 
a = int(input("Enter the value for a: "))

if a % 2 == 0:
	print("Number is even")

else:
	print("Number is odd")	
```	

Q18. What are boolean operator?
Ans. The logical operators and, or and not are also referred to as boolean operators.

Q19. What will the output of the following?
```
1 or 0 - 1

0 and 0 - 0

True and False and True - False

1 or 0 or 0 - 1
```

Q20. What are conditional statements in Python?
Ans. They are decision making statements, if, elif, else.

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans. They are used to evaluate conditions and make decisions.	

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans. 
```
age = int(input("Enter age: "))

if age>=18:
	print("I can vote")

else:
	print("I can't vote")
```

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for i in numbers:
    if i%2==0:
        sum = sum + i

print(sum)
```
Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
```
a = int(input())
b = int(input())
c = int(input())

if (a >= b) and (a >= c):
    largest = a
  
elif (b >= a) and (b >= c):
    largest = b
else:
    largest = c

print("Largest of a,b,c : "+str(largest))  
```

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
```
numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:
    if i>150 and i<500:
        continue

    if i>500:
        break

    if i%5==0:
        print(i)
```

