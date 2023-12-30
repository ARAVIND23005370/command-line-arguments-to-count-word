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
![Screenshot 2023-12-30 144508](https://github.com/ARAVIND23005370/command-line-arguments-to-count-word/assets/148514836/8db83ad8-83b8-4224-886b-07fdadc07195)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
