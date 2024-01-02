# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.

### Step 2: 
Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.

### Step 5: 
You can refine the count by cleaning the string prior to splitting or validating the words after splitting.
### Step 6: 
End the program.
## PROGRAM:
```
## DEVELOPED BY: SRIKAAVYAA T
## REFERENCE NUMBER: 23013589
num_words =0
file1 = open("nature.txt", "r")
with open('nature.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![Screenshot 2024-01-02 174357](https://github.com/Srikaavyaathamizh/Word-count/assets/144870938/c95dd9dd-3632-4e61-ac16-f86579ef503e)

## RESULT:
Thus the program is written to find the word count from a text.
