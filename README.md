# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys

### Step 2:
initially make count = 0

### Step 3:
open the content file using command line arguments.

### Step 4:
by using for loop name the function as "line"

### Step 5:
split the line using .split

### Step 6:
Running the program

### PROGRAM:
'''

Program for getting the word count from the contents of a file using command line arguments
Developed by: Daniel C
RegisterNumber: 212223240023
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)

```
### OUTPUT:
![image](https://github.com/Daniel-christal/command-line-arguments-to-count-word/assets/145742847/f800e522-90f8-4035-9f76-11566b6c14b5)

### RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
