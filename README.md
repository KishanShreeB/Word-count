# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Initialize a word count variable to zero.
### Step 2: 
 Open the specified text file in read mode.
### Step 3:
Iterate through each line in the file:

Split the line into a list of words.
Add the number of words in the line to the total word count.

### Step 4:  
Close the file.
### Step 5: 
Print the total number of words found in the file.

## PROGRAM:
```
#Program to find word count
#Developed by:Kishan Shree B
#Register No: 212223100022


num=0
with open("sample.txt","r") as f:
    for i in f:
        word=i.split()
        num+=len(word)
print("The total numbers of words n the file is",num)
```

### OUTPUT:

![image](https://github.com/KishanShreeB/Word-count/assets/144870434/497d57a6-da26-4492-8ac8-97c207ae9b5d)

![image](https://github.com/KishanShreeB/Word-count/assets/144870434/6e81458b-6112-4b6f-af9e-80dc02e6e161)





## RESULT:
Thus the program is written to find the word count from a text.
