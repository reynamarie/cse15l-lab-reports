//example of using the command with no arguments
ls
output{
     
    dog.jpg         index.md        lab1.md
}

cat
blank output{
  
}

cd
blank output{
  
}



//example of using the command with a path to a directory as an argument.
ls cse15l-lab-reports
output{
    
    dog.jpg         index.md        lab1.md
}

cat cse15l-lab-reports/index.md
output{
    
    # Lab Report 1

    This is the file I am submitting:)


    ![Image](dog.jpg)
}

cd cse15l-lab-reports
output{

    cd cse15l-lab-reports
}





example of using the command with a path to a file as an argument
ls cse15l-lab-reports/dog.jpg
{

    cse15l-lab-reports/dog.jpg
}


cat cse15l-lab-reports/dog.jpg
output{

    many random characters
}


cd cse15l-lab-reports/dog.jpg 
{
      
    cd: not a directory: cse15l-lab-reports/dog.jpg
}





