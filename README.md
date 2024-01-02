# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open python compiler and upload the text file.
### Step 2: 
Start coding ,with open(filne/...)
### Step 3: 
Declare the variables.
### Step 4:  
use for loop and Use .split(),which splits the each words in a line.
### Step 5: 
Print the woord count
### Step 6: 
End the program..
## PROGRAM:
### Program to find the Word Count.
### Developed by : JOTHIKRISHNAA V
### Register Number : 212223100017
~~~python
num=0
with open ("ex5python.txt",'r') as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("The number of words in the file are:",num)
~~~
### OUTPUT:

![word count](<Screenshot 2024-01-02 165634.png>)

## RESULT:
Thus the program is written to find the word count from a text.
