# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file from which the contents are to be copied as firstfile
### Step 2: 
 Open the file to which the contents are to be pasted as secondfile
### Step 3: 
Seprating the lines using the for loop in the first file
### Step 4:  
Writing to the secondfile using write() function

## PROGRAM:
```py
#Program to copy the contents of a file to another file
#Developed By : Sanjay Ragavendar M K
#Register Number : 22009286

with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
````
### OUTPUT:

![5 inpt](https://user-images.githubusercontent.com/91368803/215013909-3a7eba96-8481-4dd5-b41a-7693c1923bdf.png)

![5 otpt](https://user-images.githubusercontent.com/91368803/215013913-bf01a482-74da-43f7-826d-88e5b25c72c2.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
