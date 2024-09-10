# test1.0
First download the folder by downloaidng the zip file including the j2024_09_03 folder
Next you would upload said folders into a github codespace keeping the file structure.
Then in the codespace you need to change the the directory to be in said folder.
Next in the terminal you can input said command to recompile the java files into the out folder: javac -d out src/c/*.java
To compile the test file: javac -d out -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar src/u/HybridTest.java
Now to run the test file the command to run would be: java -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore HybridTest
