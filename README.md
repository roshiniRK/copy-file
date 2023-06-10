# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the required file by using the function "with" in read mode.
### Step 2: 
 Open the another required file by using the function "with" in append mode to append.
### Step 3: 
Use for loop in file1.
### Step 4:  
Use write function.
### Step 5: 
To write the file 1 content in file 2.
### Step 6: 
End the program.
## PROGRAM:
```
#Program to copy the contents from one file to another file.
#Program developed by:ROSHINI RK
#Registration number: 212222230123
```
```
with open('1.txt','r') as file1:
    with open ('copy.txt','a') as file2:
        for line in file1:
            file2.write(line)
```

### OUTPUT:
![copy](https://github.com/roshiniRK/copy-file/assets/118956165/575b798b-e558-4d16-8d26-1d92f95ace49)
![1](https://github.com/roshiniRK/copy-file/assets/118956165/c6d35f86-71cb-45be-983d-20afb4f8714f)
![ctxt](https://github.com/roshiniRK/copy-file/assets/118956165/c083f2bd-37e9-4b7f-ae54-a7da821b349f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
