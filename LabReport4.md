# Lab Report 4
## Steps 4 - 9

**Step 4**

Keys Pressed:

```
<type: ssh cs15lwi23aol@ieng6.ucsd.edu><enter>
```

This is the command that must be typed into the terminal to access the ieng6 account. I then press enter to then access the account.

**Step 5**

Keys Pressed:

```
<type: git clone><Command><V><git@github.com:ucsd-cse15l-w23/lab7.git><enter>
```

To clone the lab7 repository into the class, we need to type git clone into the terminal, paste the ssh link of the git repository into the terminal, and then click enter to clone the repository into the ieng6 account server.

**Step 6**

Keys Pressed: 

```
<type: cd lab7><enter>

<Command><C><javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java><Command><V><Enter>
  
<Command><C><java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore><Command><V><ListExamplesTests><Enter>
```

I first change into the directory in which the relevant java files are located. I access the java commmands to run the JUnit tests and copy them onto the terminal. First, I compile the tests as well as the java files. I then run the tests to see if there are any errors in the code.

**Step 7**

Keys Pressed:

```
<type: nano ListExamples.java><enter>

<down key pressed 42 times><right key pressed 12 times><delete><type: 2><Control><O><Enter><Control><X>
```

`nano ListExamples.java` enables me to edit the file and find where the error is. I identify where the error is, access that point in the file and edit it. Then I save the edit using `<control><O>` and exit the editing ability using `<control><X>`. 

**Step 8**

Keys Pressed:

```
<up><up><up><enter>

<up><up><up><enter>
```

I use the up key 3 times to first access `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` in the bash history. Then press enter to run the command. Similarly, I then press the up key again 3 times (it is the same amount because there has been a new command added) to access the `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`. Then I press enter to run the tests.

**Step 9**

Keys Pressed:

```
<type: git add><tab><enter><type: git commit -m "code fixed"><enter><type: git push><enter>
```

`git add` adds the changes made to ListExamples.java to the file. The tab key autofills the file name. `git commit` commits these changes and adds the change to the revision history of the file. Finally, `git push` pushes the changes to the file to the repository on github.
