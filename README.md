# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:Create a txt file to count the number of word in that file.

Step 2:Open the txt file in read mode using open().

Step 3:Using split() function to split the words in the txt file and count it.

Step 4:Save the python program using .py extention.

Step 5:Run the python program in terminal to get the output.

Step 6: Number of words in the txt file is displayed as the output

PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : AJAY ASWIN.M                                                                                                                                         ## REFERENCE NO :22009241
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```

### OUTPUT:

![31437490-c43b-4d96-94ad-0e7fc2d89036](https://user-images.githubusercontent.com/118626456/214857251-be1737db-32ef-457b-83e0-7b2117b54a71.jpg)


## RESULT:
Thus the program is written to find the word count from a text.
