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

Assign a variable count =0

### Step 3:

open a file in read mode

### Step 4:

iterate a variable(lines) through the file

### Step 5:

Assign a variable words = lines.split()

### Step 6:

Now iterate through the variable and increase the count: and print the count value
## PROGRAM:
```
#Developed By:- Sai Eswar Kandukuri
#Register number: 21000679
import sys
count =0
with open(sys.argv[1],'r') as f:
    for lines in f:
        words = lines.split()
        count+=len(words)
print("Number of words in a file:",count)
```
### OUTPUT:
#### Program:
<img width="768" alt="Screenshot 2022-02-22 at 2 37 19 PM" src="https://user-images.githubusercontent.com/93427011/155099183-ba9e1ee1-3c8f-4066-a842-28babac21640.png">

#### TextFile:

![Output](./toutput.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
