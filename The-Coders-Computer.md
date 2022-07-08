# The Coders Computer
<sup>Lab 2</sup>

### What is a text editor?

A text editor is a pice of software that allows you to qwrite and manage text.

### Why is it important to thoughtfully choose a text editor?

It is important to carefully choose a text editor because every editor will have diffrent features and layouts. While switch between editors is aliright to do you don't want to switch too often because it will take valuable time 
away from your project inorder to re learn a new tool. In addition, you'll want to make sure the text editor you are going to be using has the features you will need in order to complete your specific task most efficently.

### What are some Diffrent Types of Text Editors?

#### pre-installed software
On your computer, no matter what the OS, you will have some pre installed text editors that are available to you.
Wether it is "text edit" or "Notepad" these editors have basic funcionality and not many features to speak of. They do exactly what the name implies, they edit text.
So if you are wanting any extra features then i recommend looking into some third party options.

#### Third Party Software
Third party apps are usually free and able to be downloaded from a web browser. Software such as Notepad++, Text Wrangler, BB Edit, Visual Studio Code, Atom,
Brackets, and Sublime Text offer many features which make using them for code a lot easier than the pre installed software. Features like code completion, highlighting syntax, and extension will help your flow when editing text.

#### Diffrence between a text editor and an IDE
As stated above a text editor editis the text file which you are currently working on. it can also manage text and manage files. An IDE is a collection of software all compiled in one package. Not only does an IDE manage text files it also can also be a compiler, and a debugger all in one software. 
When you are just starting out using a text editor will give you a good grasp on codeing as you might not need a compiler or debugger to start off with but using a text editor can get you familiar with writeing your code.

# Terminal Cheat Sheet

Here are some useful commands when working in a terminal. These commands will help you navigate through and edit diffrent fiels while working on your project:

``` eco $SHELL ```

This command will call what shell you are currently using

``` Up and Down arrow keys ```

These will call back previously entered codes that you have typed

``` pwd ```

Print Working Directory will show you the current directory you are woking in.

``` ls ```

This will show you a list, in your current location, of files and directories. You can use the arguement **-l** to give you a long list. Inorder to show hidden files you can use argument **-a**.

``` ~ ``` 

This is a shortcut inorder to get to your home directory.

``` . (dot) ```

This refers to your current directory

``` .. (dot,dot) ``` 

This command refers to the parent directory 

``` cd ```

This changes the directory to the specified directory. If the direstory you wish to change to has a space in the name (i.e. cd 'Home Kitchen') you would suround the directory name in  quotes '' to mark it as one item.

``` man ```

This is the manuel command. if you follow it up with any command you will get a full page explaining the command and some arguments you can use with it. You can use the **-k** argument to search all the manuels for a key word. You can also use the **/<term>** argument to search the current page for a specific term.

``` mkdir ```

Makes a new directory
  
``` rmdir ```
  
Removes a directory
  
``` touch <file name> ```
  
  Using this command will creat a blank file at the directory you are currently in
  
  ``` cp<source><destination> ```
  
  This command will copy the source file to the chosen desitnation
  
  ``` mv<souce><desitnation> ```
  
  This will move the source file to the chosen destination
  
  ``` rm<file> ```
  
  this will remove the file. you can use **-r** argument to remove non empty directories and fiels. It is advisable to use argument **-i** with the previouse argument as it will promt you before deleting any fiels, that way you know what is being removed.
  
  ``` vi ```
  
  Allows you to edit a file
  
  ``` cat ```
  
  Allows you to view a files content
