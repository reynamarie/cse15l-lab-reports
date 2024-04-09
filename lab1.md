//example of using the command with no arguments
'ls'
```
{
    dog.jpg         index.md        lab1.md
}
```
The absolute path to the current working directory right before the command was run '/home/cse15l-lab-reports'
I received this output because  these are the files and or folder within the repository. 
This is not an error because 'ls' is used to list the files and folders of the given path, which is exactly what it did. 



`cat`
```
{
  
}
```
The absolute path to the current working directory right before the command was run '/Users/reynamaharaj/Downloads/cse15l-lab-reports-main.'
I received this output because the commad did not have any arguments. Therefore, there was nothing to print the contents of. 
This is not an error because 'cat'. I used the command with no arguments, and the output returned nothing because no paths were given. 



'cd'
```
{
  
}
```
The absolute path to the current working directory right before the command was '/Users/reynamaharaj/Downloads/cse15l-lab-reports-main'. Because when I put in cat, the terminal didn't return nothing, not even reynamaharaj@Reynas-MacBook-Pro ~ %. So I did ls again and then continued to 'cd.'
I received this output because the commad did not have any arguments. Therefore, there was nothing to print the contents of. 
This is not an error because 'cat'. I used the command with no arguments, and the output returned nothing because no paths were given. 



//example of using the command with a path to a directory as an argument.
`ls cse15l-lab-reports`
```
{
    dog.jpg         index.md        lab1.md
}
```
The absolute path to the current working directory right before the command was /Users/reynamaharaj. 



`cat cse15l-lab-reports/index.md`
```
{
    # Lab Report 1

    This is the file I am submitting:)


    ![Image](dog.jpg)
}
```

/Users/reynamaharaj


'cd cse15l-lab-reports'
```
{

     cd cse15l-lab-reports
}
```
/Users/reynamaharaj

//example of using the command with a path to a file as an argument
'ls cse15l-lab-reports/dog.jpg'
'''
{
     cse15l-lab-reports/dog.jpg
}
'''
/Users/reynamaharaj/cse15l-lab-reports


'cat cse15l-lab-reports/dog.jpg`
'''
{
     many random characters
}
'''
/Users/reynamaharaj/cse15l-lab-reports

'cd cse15l-lab-reports/dog.jpg'
'''
{
     cd: not a directory: cse15l-lab-reports/dog.jpg
}
'''
/Users/reynamaharaj/cse15l-lab-reports




