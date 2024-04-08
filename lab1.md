//example of using the command with no arguments
ls
rendered output output{
     
    dog.jpg         index.md        lab1.md
}


cat
blank rendered output{
  
}


cd
blank rendered output{
  
}



//example of using the command with a path to a directory as an argument.
ls cse15l-lab-reports
rendered output{
    
    dog.jpg         index.md        lab1.md
}

cat cse15l-lab-reports/index.md
rendered output{
    
    # Lab Report 1

    This is the file I am submitting:)


    ![Image](dog.jpg)
}


cd cse15l-lab-reports
rendered output{

    cd cse15l-lab-reports
}





example of using the command with a path to a file as an argument
ls cse15l-lab-reports/dog.jpg
rendered ouput{

    cse15l-lab-reports/dog.jpg
}


cat cse15l-lab-reports/dog.jpg
rendered output{

    many random characters
}


cd cse15l-lab-reports/dog.jpg 
rendered output{
      
    cd: not a directory: cse15l-lab-reports/dog.jpg
}





