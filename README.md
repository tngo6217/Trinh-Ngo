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
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture13.PNG)
- To create a dictionary we use {}, the keys have to be immutable and unique, but the values can be immutable, mutable, and duplicates.
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture14.PNG)
- Find values through keys:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture15.PNG)
- Add and delete keys and values:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture16.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture17.PNG)
- When we put "key1" in DICT, we receive a True if key1 is in the dictionary, False if key1 is not in there.
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture18.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture19.PNG)
3. Sets: They are type of collection (means we can input different Python types like lists and tuples)
- Sets are unordered (means sets do not record element position)
- Sets only have unique elements (only one of a particular element in a set)
- If we put Set1= {"pop", "rock", "soul", "hard rock", "rock", "R&B", "rock", "disco"}, Set1: {'rock', "R&B", "disco", "hard rock", "pop", "soul"}. All the "rock" will become 1 'rock'.
- We can put a list into a set 
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture20.PNG)
- To add an element into a set, use \setname\.add("\new element\"). If we add an element that is already in the set, nothing would change.
- To remove an element from a set, use \setname\.remove("\element existing in the set\").
- To check if the item is in the set or not, use "\name of the element\" in \setname\. If receive True, that item is in the set, False means the item is not in there.
- Like in Math, we can find a set that is the intersection of 2 sets:
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture21.PNG)
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture22.PNG)
- Also, we can fine the union of 2 sets:
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture23.PNG)
- To check if set A is a subset of set B, use A.issubset(B). True means A is in B, False means A is not a subset of B.
### Week 3: Python Programming Fundamentals
1. Conditions and Branching
- Boolean to compare values:
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture24.PNG)
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture25.PNG)
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture26.PNG)
- Branching: 
- If statement. Ex: If you're older than 18, you can enter the concert, else you can't
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture27.PNG)
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture28.PNG)
- Elif statement:
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture29.PNG)
- Logic operators, just like in Math: not(True) is False, not(False) is True.
- "or" condition
  ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture30.PNG)
- "and" condition
  ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture31.PNG)
 2. Loops: There are While loops and For loops. We just apply For loops if we know how many times we're going to run the same thing.
 - range(N) means the values will start from 0 to N-1. Ex: range(10,15) => [10,11,12,13,14].
 - For loops: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture32.PNG)
 ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture33.PNG)
 - While loops: is similar to for loops but we use it when we don't know how many times we're going to run the same thing.
 ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture34.PNG)
3. Functions: Pyhton has many built-in functions
- Len function takes in an input of type sequences (list, string, tuple, or dictionary) and tell us how many elements are in there.

- Sum function adds the values in a list 

- There are 2 ways to sort a list: sorted function and sort function 
- Sorted just changes the list when the list is with sorted function

- Sort changes the original list 

- Definition function is written def and it's to help us make new functions, followed by a discpripted name of a function and its formal parameters in parentheses and followed by a colon. Code block is the indent part below that line. After we define a function, we can use it like this:
- 
- help (add1) helps define how that function add1 works







