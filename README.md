# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Import the sys module.

## Step 2:
Define a function get_word_count(file_path) to calculate the word count in the file.

## Step 3:
Check if the script is being run as the main program

## Step 4:
Check if the correct number of command-line arguments (i.e., 2) is provided.

## Step 5:
Get the file path from the command-line argument

## Step 6:
Print the word count if it is not None.

## Step 7:
End the program

## PROGRAM:
```

#Program to for getting the word count from a text.
#Developed by:PRAVIN KUMAR A
#Register Number:23004448
import sys
fp=open(sys.argv[0],'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print('Number of words in a file',count)
```
### OUTPUT:
![5b (2)](https://github.com/RAVENPRAVIN/command-line-arguments-to-count-word/assets/146820534/c942994b-0b8f-436e-8123-c5e5b02fb51b)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
