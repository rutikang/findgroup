# findgroup

findgroup enables to search for file with a specific extension within a directory recursively and copies those files into a specific directory of your choice. The default files are c files but different flags can be used to see the different options of file extensions. These can be seen using the -h | --help flag. 

**Importance**

findgroup makes it easy to group files with a specific extension in the same directory and fast.

**Usage**

findgroup [options] [directory path]

  default sends a copy of all c files to the desired directory. 
  
  **Testing the script**
  
  test_script is a script used to test the findgroup script.
  
  **Usage of test script**
  
  test_script findgroup
  
  test_script followed by findgroup
  
  To test both the scripts(findgroup and test_script) need to be in the same directory and the directory should have the files to copy. 
  For testing purposes the destination directory paths have been created in scottyone in /home/krutikan as n2,'n 3',n4 and n5.
  For each new test the new files created in these directories need to be deleted otherwise the files already exist in the destination.
