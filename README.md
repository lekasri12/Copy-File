# DATE
# EX-11 Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Get the file name and location from the user.

## Step 2:
Give a new file name to create a copy of a file content.

## Step 3:
Read the file and close the file.

## Step 4:
Now write the content in the new file.

## Step 5:
When done print"File copied successfully".

## Step 6:
End of the program

## PROGRAM:
```
#Copy contents of a file 
#Developed by: BHUVANESHWARI M
#Register Number:212223230033
with open("text1.txt","r") as fp:
    msg1=fp.read()
with open("copytxt","w") as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![Screenshot 2024-10-16 112911](https://github.com/user-attachments/assets/0ab2b978-e962-45f0-9afd-0edb48d6a9da)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
