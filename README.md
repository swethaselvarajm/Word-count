# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open then required file by using the function"with"
### Step 2: 
Using split function to split the words.
### Step 3: 
Finding the length of the words by using len() function.
### Step 4:  
Calling the function and printing the number of words.

## PROGRAM:
```
#Developed By: SWETHA.S
#Register No: 212222230155
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of words:",wordslen)
```
### INPUT:

![Screenshot 2023-11-04 170447](https://github.com/swethaselvarajm/Word-count/assets/119525603/f1008f45-e796-4c3c-b90e-aee7f1c5642e)

### OUTPUT:

![Screenshot 2023-11-04 170428](https://github.com/swethaselvarajm/Word-count/assets/119525603/8efd3a09-4d1e-4308-b49c-c5d4758c93d5)

## RESULT:
Thus the program is written to find the word count from a text.
