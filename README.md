# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:  Open then required file by using the function"with"

### Step 2:  Using split function to split the words.
 
### Step 3: Finding the length of the words by using len() function.

### Step 4: Calling the function and printing the number of words.

## PROGRAM:
```
#Developed By:Jeyabalan
#Register No: 212222240040
n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```
### OUTPUT:
![image](https://github.com/jeyaqbalan7/Word-count/assets/119393851/2394ab68-8af7-467e-8a4b-bf2273046064)

## RESULT:
Thus the program is written to find the word count from a text.
