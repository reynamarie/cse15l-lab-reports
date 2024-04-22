//example of using the command with no arguments

    'ls'
```
{
    cse15l-lab-reports dog.jpg         index.md        lab1.md
}
```

So the way in which I found the absoulate path before the command was ran was by running giving it the previous command and using pwd. The absolute path to the current working directory right before the command was run '/home/cse15l-lab-reports'. For this one I began with just pwd. 
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
This is not an error because I used the command with no arguments, and the output returned nothing because no paths were given. 






//example of using the command with a path to a directory as an argument.
`ls cse15l-lab-reports`
```
{
    dog.jpg         index.md        lab1.md
}
```
The absolute path to the current working directory right before the command was /Users/reynamaharaj. 
I received this out put because I used ls to list the paths/files in the cse15l-lab-reports-main directory. 
This is not an error because ls lists the files in the curret directory, and  dog.jpg         index.md        lab1.md is what I made in the current directory. 

`cat cse15l-lab-reports/index.md`
```
{
    # Lab Report 1

    This is the file I am submitting:)


    ![Image](dog.jpg)
}
```

The absolute path to the current working directory right before the command was Users/reynamaharaj. 
I recived this output because cat is reading the contents of the index.md file int the cse15l-lab-reports directory. 
This is not an error because this is the correct contents of the correct file that I ran the command on. 


    'cd cse15l-lab-reports'
```
{


}
```
The absolute path to the current working directory right before the command was /Users/reynamaharaj. 
I recived this because cd is used to chnage directories, not chnage it. 
THis is not an error, it is not printing anything as expected. After running it I can run pwd locally and recieve /Users/reynamaharaj/cse15l-lab-reports, which verifies that this is the new current working directory.








//example of using the command with a path to a file as an argument

    'ls cse15l-lab-reports/dog.jpg'
'''
{
            
    cse15l-lab-reports/dog.jpg
}
'''
The absolute path to the current working directory right before the command was /Users/reynamaharaj/cse15l-lab-reports. 
As mentioned before ls is used to list the files of a directory. However, when I use the directory and the file path as an argument, it will just return the filename if it exists. Which is the reason for the recived output. 
This is not an error, the file exists, so the directory and the file given was printed. 


    'cat cse15l-lab-reports/dog.jpg`
'''
{
   
     many random characters
}
'''
The absolute path to the current working directory right before the command was /Users/reynamaharaj/cse15l-lab-reports. 
I recived a bunch of random charcaters because cat is used to print the contents of the working directory. dog.jog is a binary file, so the terminal bcould not display it. Its like it was attemptiing to display textfile from an binary file, which is the reason this I did not display as such. Also why I might consider an error. Howeever, this is the output that will be given if called upon in such way. 




'cd cse15l-lab-reports/dog.jpg'
'''
{
    
    cd: not a directory: cse15l-lab-reports/dog.jpg
}
'''
The absolute path to the current working directory right before the command was /Users/reynamaharaj/cse15l-lab-reports/cse15l-lab-reports-main. 
I recived this output because dog.jpg is a file and the directory cannot be chnaged into the file. 
This is an error message because you cannot cd with a file as an argument. 




