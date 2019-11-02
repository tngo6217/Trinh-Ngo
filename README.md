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
-   I have to skip the Analyzing US Economic Data and Building a Dashboard of Course 1, Final Assignment, and IBM Digital Badge of Course 2 because I cannot access them with free audit.
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
3. Python Programming Fundamental (3 hours)
4. Python Programming Fundamental (continued) (2 hours)
5. Working with Data in Python (4 hours)
6. Working with Data in Python (continued) (3 hours)
7. Importing Datasets (2 hours)
8. Data Wrangling (2 hours)
9. Exploratory Data Analysis (2 hours)
10. Model Development (2 hours)
11. Model Evaluation (2 hours)

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
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture35.PNG)
- Sum function adds the values in a list 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture36.PNG)
- There are 2 ways to sort a list: sorted function and sort function 
- Sorted just changes the list when the list is with sorted function
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture37.PNG)
- Sort changes the original list 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture38.PNG)
- Definition function is written def and it's to help us make new functions, followed by a discpripted name of a function and its formal parameters in parentheses and followed by a colon. Code block is the indent part below that line. After we define a function, we can use it like this:
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture39.PNG)
- help (add1) helps define how that function add1 works
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture40.PNG)
- A function can have multiple parameters. Ex: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture41.PNG)
- In the same case, if we put Mult(2, "Hello"), the result c will become "Hello Hello"
- In some cases, a function doesn't have a return statement, Python will return to "None" 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture42.PNG)
- The above example contains pass which does nothing but to satisfy the requirement of a none empty body then when we print it out, the result will be 'None'.

### Week 4: Python Programming Fundamentals (continued) 
- More things we can do with def functions:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture43.PNG)
- We can use loops in functions
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture44.PNG)
- In the example above, Stuff is album_ratings for s is the values in there. So everytime i reach to the index 0, 1, 2, Python will print out the correspongding value of that index, and it will stop until the last index printed out.
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture45.PNG)
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture46.PNG)
- The asterisk on the parameter names allows us to include all elements of the tuple ArtistNames. The values will be printed out to the according length.  
4. Objects and Classes:
- Every object in Python has a type, an internal data representation (a blueprint), a set of procedures for interacting with the object (methods)
- An object is an instance of a particular type, ex: 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture47.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture48.PNG)
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture49.PNG)
- A class or type's methods are functions that every instance of that class or type provides.
- It's how we interact with the data in a object
- Sorting is an example of a method that interacts with the data in the object
- Ex: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture50.PNG)
- We can create our own type of class in Python:
- Class is composed of Data Attributes, Methods. Imagine we're creating Class Circle and Class Rectangle:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture51.PNG)
- Here are what we need to create that with the instances:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture52.PNG)
![Sampke](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture53.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture54.PNG)
- Function init is a contructor, telling Python that we're making a new class
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture55.PNG)
- If we combine them:![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture56.PNG)
- To change "red" to "blue", we can do C1.color="blue"
- Methods of class: to extend radius:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture57.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture58.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture59.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture60.PNG)
- We can add default values for parameters, such as def_init_(self, radius=3, coloe='red'):
- New method: 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture61.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture62.PNG)

### Week 5: Working with Data in Python
1. Reading Files with Open
- Python can help open a file object by using: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture63.PNG)
with open("/resources/data/Exmaple2.txt","w") is the file path, Example2.txt is the file name, /resources/data/ is the directory. The second parameter which is "w" is the mode (w means writing, r for reading, and a for appending).
- To obtain information about the file: File1 is the file object in this case,  put fileobject.name (File1.name) to search for the name of the file, or put File1.mode to search for what kind of mode in the second parameter. We can close the file using File1.close().
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture64.PNG)
- Using a 'with statement' to open a file is better because it will automatically close the file
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture65.PNG)
- The method read (the second row in the above picture), stores the value of the file in the variable file_stuff as a string
- We can output every line as element in the list by using the method readlines()
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture66.PNG)
- The first line corresponds the first element of the list and so on.
- The method readline() is to read the first line of the file. We can put 2 readline lines like this, 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture67.PNG)
so the "This is line 1" or so on would appear depends on how many lines we put down.
- We can use loop to print lines too: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture68.PNG)
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture69.PNG)
- Each time we cal the method readlines, we will progress through the text
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture70.PNG)
2. Writing Files with Open: The order is gonna be the same as reading files with open, just change the mode from "r" to"w"
- ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture71.PNG)
- To create the object file (File1), the first line in the picture shows us how to do it. Then put the content in the File1.write (can write as many as we want). Everytime the code runs, it will call each line to get the content and put it to the Example2.txt, and close the file.
- We can write each elemant to the list, then use for loop to put those elements from the list to the file. At the end of the loop, the file will be closed: 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture72.PNG)
- If we change the mode to "a" (means appending), we can add another content into Example2.txt by using File1.write("\content\")
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture73.PNG)
- We can copy one file to a new file by this following:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture74.PNG)
3. Loading Data with Pandas:
- Pandas is the common library in Python.
- Csv is the typical file type used to store data. 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture75.PNG)
- Typing Pandas all the time may get tedious, so we can use the 'as statement' to shorten the name of the library. In the as statement, after the word as, we can put any letter that we want to make a shortcut, then follow this: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture76.PNG)
- Pandas allows us to work with data on dataframe. Here is the process to go from a cvs file to a data frame:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture85.PNG)
- The csv_path= 'file1.csv' stores the path of the csv, and it is used as an argument to the read_csv function on the second line. The result is stored to the variable df (dataframe). Now we have the data in a data frame, so we can work with it. 
- The method head helps us examining the first five rows of a data frame. (similar in Excel)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture77.PNG)
- A data frame is composed of rows and columns. We can create a data frame out of a dictionary. The keys correspond to the column labels, and the values or lists correspond to the rows. Then we can cast the dictionary to a data frame using the function data frame: 
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture78.PNG)
- We can create new data frame consisting of 1 or more columns by using:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture79.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture80.PNG)
- ix method is the way to access unique elements:
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture81.PNG)
![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture82.PNG)
- We can also slice data frames and assign the values to a new data frame.
- numbers of rows and numbers of columns: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture83.PNG)
- numbers of rows and names of the columns: ![Sample](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture84.PNG)
4. Working with and Saving Data: 
- Pandas has the method unique to determine the unique elements in a column of a data frame.
- Ex: we would like to determine the unique year of the albums in the data set, we enter the name of the data frame, then enter the name of the column released within brackets. Tehn apply the method unique 
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture86.PNG)
- With this method, we can get the unique values of numerous elements
- To find information of the albums released after 1979: 
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture87.PNG)
- Plug that to the variable df1, we'll get this: 
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture88.PNG)
- Save as CCV: The argument is the name of the csv file with the .csv extension. Ex: df1.to_csv('new_songs.csv')
5. One Dimensional Numpy: Numpy is a library for scientific computing. It has many useful functions, advantages like speed and memory. It's also the basis for pandas
- Numpy array: a Numpy array or ND array is similar to a list.
- To creat a Numpy array:
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture89.PNG)
- Then the value of a would be stored as:![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture90.PNG)
- If we want to check the type of the array we get: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture91.PNG) 
- As Numpy arrays contain data of the same type, when we type a.dtype (dtype is the attribute), we'll get dtype('int64') 
- We can use array attribute by casting a (or anything else). When we check the size, dimension, or shape (a tuple of integers indicting the size of the array in each dimension:
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture92.PNG)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture92.PNG)
- Indexing and Slicing:
- We can change the value of the elements by: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture94.PNG)
- Slicing like lists and tuples: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture95.PNG)
- Assign new value: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture96.PNG)
- Basic Operations: 
- Vector addtion:
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture97.PNG)
- The image above shows us the difference between adding vectors in Numoy (on the lest side) and in regular way (on the right side). It's easier to code this using Numpy. 
- Same thing for vetor subtraction, we just need to change + to -:
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture98.PNG)
- Array multiplication with a Scalar. Using Numpy only requires one line of code: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture99.PNG)
- Product of 2 numpy arrays: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture100.PNG)
- Dot Product: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture101.PNG)
- Adding Constant to an numpy array: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture102.PNG)
- To calculate the average by using mean method (a.mean): ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture103.PNG)
- To find the maximum value by using the max method (b.max): ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture104.PNG)
- To create a function and make it calculate like in math: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture105.PNG)
- linspace is a useful fuction for plotting: 
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture106.PNG). We can see the spaces between the numbers are 1
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture107.PNG). We can see the spaces between them is 0.5
- Plotting mathematical functions: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture108.PNG)
### Week 6: Working with Data in Python (continued):
6. Two Dimensional Numpy (2D array):
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture109.PNG)
- We use the attribute ndim to obtain the number of axes or dimensions referred to as the rank. In this case, the result is A.ndim: (2 dimensions)
- ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture110.PNG)
- To access the element: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture111.PNG)
-  Slicing: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture112.PNG)
- Add matrix: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture113.PNG)
- Multiply matrix: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture114.PNG)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture115.PNG)
- Dot product: ![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture116.PNG)
![Image](https://github.com/tngo6217/Trinh-Ngo/blob/master/Capture117.PNG)
7. Simple APIs (part 1): Cannot access this video for free 
8. SImple APIs (part 2): Cannot access this either. Too bad, so sad.
### Week 7: Importing Datasets
1. The problem: Before we begin talking about the problem, used car prices, we should first understand the importance of data analysis. Data is clloected everywhere around us, whether it's collected manually by scientists or collected digitally everytime we click on a website, or our mobile device.
- Data analysis/data science helps us answer questions from data. Data analysis plays an important role in: discovering useful information, answering questions, predicting future or the unknown.
- Our setting is in the following image: 
-118
- If we think like scientists, the attributions to determine the price of Tom's car is: 119.
2. Understanding the Data: 
- The dataset used in this course is an open dataset by Jeffrey C. Schlemmer, and it's in CSV format, which separates each of the values with commas, making it very easy to import in most tools or applications. Each line represents a row in the dataset.
- 120
- Sometimes the first row is a header, which contains a column name for each of the 26 columns, but in this example, it's just another row of data.
- 121
- The picture above is the documentation on what each of the 26 columns represent.
- The first attribute "symboling" corresponds to the insurance risk level of a car. So on a scale from -3 to 3, a plus 3 indicates that the auto is risky, and a minus 3 is probably safe.
- The second attribute "normalized-losses" is the relative average loss payment per insured vehicle year. This value is normallized for all autos within a particular size classification like 2 door small, station wagon, sport specialty, etc., and represets the average loss per car per year. 
- After we understand the meaning of each feature, we'll notice that the 26 attribute is price. This is our target value. this means price is the value that we want to predict from the dataset and the predictors should be all the other variables listed like "symboling".
3. Python Packages for Data Science: 
- To do data analysis in Python, we should first know a little bit about the main packages relevant to analysis in Python. 
- A Python library is a collection of functions and methods that allow you to perform lots of actions without writing any code. It contains bulit in modules providing different functionalities which you can use directly. There are extensive libraries offering a braod range of facilities. We have divided the Python data analysis libraries into 3 groups: scientific computing libraries, visualization libraries, and algorithmic libraries.
- 122
- 123
- 124
4. Importing and Exporting Data in Python: 
- Data acquisition is a process of loading and reading data into Python from various resources. 
- To read any data using Python's pandas package, there are 2 important factors to consider: format and file path. Format is the way data is encoded. We can tell different encoding schemes by looking at the ending of the file name. Some common encodings are: .csv, .json, .xlsx, .hdf...
- The path tells us where tha data is stored (could be on computer or online). 125
- In Pandas, the read.csv method can read in files with columns separated by commas into a pandas data frame. Reading data in pandas is quick: import pandas, then define a variable with a file path, then use read.csv method to import the data (read.csv saaumes the data contains a header, our data on used cars has no comun headers, so we need to specify read.csv to not assign headers by setting header to None)
126
- Printing the dataframe in Python: 127
- Since we set up header to none, so it came out with integers like in the picture
- If we want to add headers: 128 then it will become 129.
- To export the pandas dataframe to a new .csv file: 130.
- There are different formats in Python to import and export data using pandas, 131.
5. Getting Started Analyzing Data in Python: 
- Basis insights from the data: understand your data before beginning any analysis. Pandas has many built-in methods that can be used to understand the datatype or features or to look at the distribution of data within the dataset. Then it would help locating potential issues with the data.
- This table shows the differences and similarities between pandas type and native python type. 132.
- Checking data types is to locate potential info and type mismatch, and it allows an experienced data scientists to see which python functions can be applied to a specific column. 
- 133.
- To get the quick statistics, we use the describe method. It returns the number of terms in the column as count, average column value as mean, column standard deviation as std, the max/min values as well as the boundary of each of the quartiles. It's possible to make the describe method worked for object type columns as well. 
- 134.
- To enable a summary of all columns, we could add an argument (includes="all"). The outcome shows the summary of all the 26 columns, including object typed attributes. 
- 135.
- NaN which stands for not a number. It's bc that particular statistical metric cannot be calculated for that specific column data type.  
- Another method to check dataset: 136.
- This function shows the top 30 rows and bottom 30 rows of the dataframe. 
### Week 8: Data Wrangling:
1. Pre-processing Data in Python: 
- Data pre-processing is the process of converting or mapping data from the initial "raw" form into another format, in oder to repare the data for further analysis. It's called data cleaning or data wrangling.
- In Python, we prform operantions along columns, each row of the column represents a sample. We access a loumn by specifying the name of the column.
- Ex: access "symboling" and "body-style" 137
- Or we can add a value to each entry of a column: 138
2. Dealing with Missing Values in Python:
- When no data value is stored for feature for a particular observation, this feature has a missing value. Missing value in data set appears as question mark and a zero or just a blank cell.
- 139.
- 140.
- In some cases we may simply want to leave the missing data as missing data because it maybe useful to keep that observation even if some features are missing. 
- To drop missing data values: .dropna is the built-in function in Pandas that helps dropping missing values. We can choose to drop rows or columns that contain missing values like NaN.
- 141
- To replace missing values: .replace is the built-in function in Pandas that helps replacing missing values. 
- First we have to calculate the mean of the column, then use .replace method to specify the value we would like to be replaced as the first parameter. The second parameter is mean as the example. 
- 142
3. Data Formatting in Python: 
- 143 
- 144
- To correct data types: 145
4. Data Normalization in Pyhton:
- This example shows how important it is to normalize data: 
- 146
- 147
- We can apply the normalization method on the length feature by those code.
- 148
- 149
- 150
- Mean method will return the average value of the feature in the data set, and std method will return the standard deviation of the features in the data set.
5. Binning in Python:
- 151
- In the actual car data set, "price" is a numerical variable ranging from 5188 to 45400, it has 201 unique values, so we can categorize them into 3 bins: low, medium, high.
- The numpy function "linspace" is to return the array "bins" that contains 4 equally spaced numbers over the specified interval of the price. Then we create a list "group_names" that contains the different bin names. Then we use the Pandas function "cut" to segment and sort the data values into bins.
- 152
6. Turning categorical variables into quantitative variables in Python:
- The fuel type feature as a categorical variable has 2 values, gas or diesel (in string format). 
- For further analysis, we have to convert these variables into some form of numeric format 
- 153.
- We encode the values by adding new features correspoding to each unique element in the original feature we would like to encode. 
- Ex: 154
- In Pandas, we can use get_dummies() method to convert categorical variables to dummy variables.
- 155
- The get_dummies method automatically generates a list of numbers, each one corresponding to a particular category of the variable.
### Week 9: Exploratory Data Analysis:
1. Exploratory Data Analysis: 
- 156
- 157
2. Descriptive Statistics:
- Describe basic features of data, and giving short summaries about the sample and measures of the data.
- 158
- It shows the mean, the total number of data points, the standard deviation, the quartiles, and the extreme values. Any NaN values are automatically skipped in these statistics.
- One way we can summarize the categorical data is by sing the function value_counts. We can change the name of the column to make it easier to read.
- Ex: 159
- Box plots are great way to visualize numeric data
- 160
- Box plots also display outliers as individual dots that occur outside the upper and lower extremes.
- 161
- Using box plots, we can see the distribution of different categories of the drive wheels feature oover price feature. 
- 162 
- 163 
- We see that as the engine size goes up, the price of the car also goes up.
3. GroupBy in Python:
- 164
- 165
- Pick out 3 data column we're interested in. Then group the reduced data according to drive wheels and body style in the second line   
- 166
- 167
4. Correlation:
- 168
- Correlation is not causation
- 169
- 170
- 171
5. Correlation-Statistics:
- 172
- 173
- 174 
- We can see a diagonal line with a dark red color, indicating that all the values on this diagonal are highly correlated. This correlation heatmap gives us a good overview of how the different variables are related to one another and most importtantly, how these variables are related to price. 
6. Analysis of Variance ANOVA:
- Statistical comparison of groups. Ex: average price of different vehicle makes.
- 175
- The diagram shows the average price of different vehicle makes. But we can't tell which category in the make feature has the most and which has the least impact on the car price prediction.
- 176
- 177
- Look at the diagram, assume that group one is Honda and group 2 is Subaru, both are the make feature categories. Since the F-score is small, the correlation between price as the target variable and the groupings is weak.
- 178 
- In the second diagram, we see a case where the F-test score would be large. The variation between the averages of the 2 groups is comparable to the variations within the 2 groups. Assume that group 1 is Jaguar and group 2 is Honda. Since the F-score is large, thus the correlation is strong in this case.
- 179
### Week 10: Model Development:
1. Model Development:
- A model can be thought of as a mathematical equation used to predict a value given one or more other values. 
- Relating one or more independent variables to dependent variables.
- 180
- Usually the more relevant data you have, the more accurate your model is.
- 181
- 182
- 183
2. Linear Regression and Multiple Linear Regression:
- 










