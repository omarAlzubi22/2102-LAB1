LAB1 instructions:

1: Download zip file containing Lab1 folder
2: Upload folder into codespace in order to maintain file arrangment
3: Update directory to previously stated folder
4: In order to recompile java folders into 'out' file, type following command into terminal:  'javac -d out src/c/*.java'
5: In order to compile our test file, simply type the following comand into terminal:  'javac -d out -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar src/u/HybridTest.java'
6: Finally, type the following command into the terminal in order to run the tes file previously compiled:  'java -cp out:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore HybridTest'
