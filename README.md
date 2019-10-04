### Goals

-   Complete the Applied Data Science Specialization 

### Boundaries / Scope

-   Complete Course 1 Python for Data Science and AI
-   Complete Course 2 Data Analysis with Python

### Success criteria

-   My own application for data retrieval and processing.
-   Weekly work log with screenshots and summaries to demonstrate activity.

### Constraints

-   I will be auditing the course for free so will be able to read and view the course content but not submit projects or earn the certification.

### Assumptions

-   The courses will be available for the duration of the semester.
-   I have all required software.

### Stakeholders

-   Professor - for grade
-   Parents - investing in my education and future success, want to make them proud
-   Perspective Employers - artifact will be added to my student portfolio which could help with getting a job

### Timeline

Week:

1. Python Basis (3 hours)
2. Python Data Structures (5 hours)
3. Python Programming Fundamental (5 hours)
4. Working with Data in Python (4 hours)
5. Analyzing US Economic Data and Building a Dashboard (3 hours)
6. Importing Datasets (2 hours)
7. Data Wrangling (2 hours)
8. Exploratory Data Analysis (2 hours)
9. Model Development (2 hours)
10. Model Evaluation (2 hours)
11. Final Assignment (4 hours)
12. IBM Digital Badge (2 minutes) 
### Week 1: Python Basics
1. Types: In Python, there are different types of data. It could be an integer (3), a real number (9.67), or word/sentence which are called string ("Hello")

- To type an integer: type(3). To type a real number: type(9.67). To type a string: type("Hello").
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Screenshot%202019-10-01%20at%209.42.48%20PM.png)

- If we type float(2), it becomes 2.0; int(1,1), it becomes 1. We can also convert numbers to a string by typing str(1) or str(9.84). The result is gonna be '1' or '9.84'.

- Boolean is also a type in Python with 2 values True or False. If we cast True for an integer 1, and false to 0, when we type int(True) we get 1, int(False) we get 0. Similarly, bool(1) --> True, and bool(0) --> False.

2. Expressions and Variables: Expressions describe a type of operation the computer performs. 
- Mathemetical operations: + adding, - subtracting, * multiplying, or / dividing (the results could be float). We can use // for integer division (ex: 25//6=4 the result is rounded).
- Python follows Mathematical conventions (ex: 3+4/2= 5, it follows dividing first and adding later).

- Variables is to store values. We can assign variables by using : or = (ex: number: 3, or number=3).
- We can store variable of an expression (ex: x: 6+4*5. The result is 26, then x=26).
- We can perform operations on x and save the result on a new variable (ex: x= 26, y=x/2 => y=26/2=13).

3. String Operations: In Python, a string is a sequence of characters. It can be expressed in double quotes or single quotes.(ex: "hello" or 'hello').
- It can be spaces or digits, and also be special characters (ex: "Hello! Do you know 1+1 can be 2 or 11 in Python?")
- Slicing, stride, tuples: slicing (length of the string)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture.PNG)
![Iamge](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture1.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/2019-10-02%20(3).png)
- Escape Sequences: .\ are meant to proceed escape sequences (strings that are difficult to input)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/string.PNG)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/string%202.PNG)
- String: Immutable  
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture2.PNG)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture3.PNG)
- Method:
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture4.PNG)
- We can also replace name in string 
- Ex: a='Michael Jackson'
-     b= a.replace ('Michael', 'Janet'). Then result will be b: 'Janet Jackson'.
- The method find:
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture5.PNG)

### Week 2: Python Data Structures

1. List and Tuples: 
- Tuples are an ordered sequence. They are written as comma-separated elements within parentheses. Ex: Rating=(0,1,2,3,4)
-Different types of variable such as string, integers, or float can be contained in a tuple. Ex: tuple1= ('hello', 1, 6.56) and the type of tuple1 is tuple
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture6.PNG)
- We can add more elements in tuple. Ex: tuple1=('hello',1,6.56). If we put tuple2= tuple1+('there', 3), the result will be tuple2= ('hello',1,6.56,'there',3)
- Similar to string, we can do slicing on tuples. To count the elements in tuples, use len(). Tuples are also immutable.
- We can put tuples inside of a tuple
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture7.PNG)

-Lists: they are also ordered sequences and are mutable. A list is represented in square brackets. Ex: L= ['hello',1,7.5]
- A list can contain another list, or another tuple. Ex: L= ['hey there', 1,2.5, ['yo',4],('abc',3.4)]
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture8.PNG)
- Just like tuple, we can do slicing with list add more elements in the existing list. Notice: L.extend('pop',10]) <=> L1= L+['pop',10]. But if we put L.append(['pop',10]), the list will become L= ['hello',1, 7.5, ['pop',10]]
- It's mutable, so we can change it like this
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture9.PNG)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture10.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture11.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture12.PNG)
- We can clone a list. Assume A and B have the same list of ['hard rock', 1,4.76]. If we change A[0]: 'banana', A will become ['banana', 1, 4.76], but B wont't change. Cloning B from A, type B = A[:].
2. Dictionaries: 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture13.PNG)
- To create a dictionary we use {}, the keys have to be immutable and unique, but the values can be immutable, mutable, and duplicates.
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture14.PNG)
- Find values through keys:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture15
- Add and delete keys and values:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture16.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture17.PNG)
- When we put "key1" in DICT, we receive a True if key1 is in the dictionary, False if key1 is not in there.
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture18.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture19.PNG)
3. Sets: 

