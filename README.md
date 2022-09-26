# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.

### Step 2:
Assign count = 0.
 
### Step 3: 
Open the text file in read mode.

### Step 4:
Read the contents using for() loop.

### Step 5:
Split the words using built-in function split().  

### Step 6: 
Increament the word count by using built-in function len().

### Step 7: 
Print the output.

## PROGRAM:
```python
'''
Program to get the word count from the contents of a file using command line arguments.
Developed by: R LAKSHANA
RegisterNumber: 22004909
'''
import sys
count = 0
with open(sys.argv[1],'r') as f:
    for line in f:
        word = line.split()
        count += len(word)
print("Word Count in File = ",count)
```

## OUTPUT:

![python_file](/PythonFile.png)

![text_file](/TextFile.png)

![output](/Output.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
