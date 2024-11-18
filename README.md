# EX-11 Copy-File
# DATE:
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
#Developed by: G LEKASRI
#Register Number:212223100025
with open("TEXT.txt","r") as fp:
    msg1=fp.read()
with open("COPY.txt","w") as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![Screenshot 2024-10-16 150704](https://github.com/user-attachments/assets/b8170660-6067-4d7b-b70b-914562974ae0)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
