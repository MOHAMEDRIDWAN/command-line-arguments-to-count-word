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
Then decleare count is equal to 0
### Step 3: 
read the file with python file name
### Step 4:  
After splitting count the number of words in the line
### Step 5: 
In last statement give the print statement
### Step 6: 
In last statement give the print statement
## PROGRAM:
```
#Developev by: Mohamed Ridwan A
#Referebce Number
import sys
count=0
with open(sys.argv[1],'r) as f:
    for line in f:
    word=line.split()
    count+=line.(word)
print("Word Count in File=",count)

### OUTPUT:
<img width="835" alt="image" src="https://github.com/MOHAMEDRIDWAN/command-line-arguments-to-count-word/assets/146993368/2d2ab659-a58a-4f1d-80b5-7f11d62cff08">


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
