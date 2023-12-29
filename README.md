# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```
# program to count the number od word count
# Developed by : Shashank R
# Register Number : 212223230205
fname = input("enter the file name")
num_words = 0
with open(fname,'r') as f:
    for line in f:
        words = line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```

### OUTPUT:
![image](https://github.com/Shashank2006offl/Word-count/assets/147140026/347dba7b-01b6-40f7-a989-2a9aa9a3a007)
![image](https://github.com/Shashank2006offl/Word-count/assets/147140026/92e87de5-9c64-4196-b2f2-03caca2c855d)
## RESULT:
Thus the program is written to find the word count from a text.
