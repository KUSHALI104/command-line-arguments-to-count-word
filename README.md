# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Run the program to determine the number of words in the file created. 

## PROGRAM:
```
'''
Developed by : KUSHALI P G
Registered number : 23012804
'''
import sys
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![Screenshot 2023-12-24 180558](https://github.com/KUSHALI104/command-line-arguments-to-count-word/assets/150231135/f1fe928e-5f4c-4afb-a0b3-f89290bc3a23)
![Screenshot 2023-12-24 180320](https://github.com/KUSHALI104/command-line-arguments-to-count-word/assets/150231135/c04c325d-985f-4b8d-bfd0-b4bc3f796f67)
![Screenshot 2023-12-24 180742](https://github.com/KUSHALI104/command-line-arguments-to-count-word/assets/150231135/550943f2-8126-4c67-84ad-211603cde8b6)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
