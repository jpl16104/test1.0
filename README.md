# test1.0
# Instructions
## Step 1:
First download the folder by downloaidng the zip file including the j2024_09_03 folder
## Step 2:
Next you would upload said folders into a github codespace keeping the file structure.
## Step 3:
Then in the codespace you need to change the the directory to be in said folder.
## Step 4:
### Next in the terminal you can input said command to recompile the java files into the out folder: 
javac -d out src/c/*.java
## Step 5:
### To compile the test file:
javac -d out -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar src/u/HybridTest.java
## Step 6:
### Now to run the test file the command to run would be: 

java -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore HybridTest
