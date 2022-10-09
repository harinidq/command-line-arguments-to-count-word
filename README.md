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
Open file using commandline arguments.
 
### Step 3:
Using for loop find the word count from the contents of a file.


### Step 4:  
Use len to count number of words.

### Step 5:
Give print statement.


### Step 6: 
End the program.


## PROGRAM:
python
#Developed by:harini.m.d
#Registration no:22001980
import sys
count=0
with open(sys.argv[0],'r') as f:
    for line in f:
        word = line.split()
        count+= len(word)
print("World Count in File = ",count)   


### OUTPUT:
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202022-10-09%2015-31-15.png![image](https://user-images.githubusercontent.com/113497680/194750976-87aa9a05-de6f-47a1-8a2c-84dd75145bf8.png)
file:///home/sec/Pictures/Screenshots/Screenshot%20from%202022-10-09%2015-40-29-1.png![image](https://user-images.githubusercontent.com/113497680/194751029-9b40aa67-82ba-40e1-bfc9-178b7df43c42.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
