# git and GitHub

## What's a git?

git lets multiple developers work on the same code together. It allows you to make changes to files and repositories without stepping over someone else's changes they are making at the same time.

## Why is it called GitHub?

GitHub is not git. GitHub is a way to share your code with others. It uses git in order to help you manage your team's work. With both git **and** GitHub you can easily manage your temas work and past versions of the code you are working on.

## ACP is what you need

In order to work on a file that is from GitHub you first have to cd into the directory that contains your copy and pasted repository, then run `code .` to open VS code and edit it. If you have made changes to your file, there is a specific set of steps you have to go through in order for those updates to show in the live repository on GitHub, these steps are Add, Commit, Push.

### Add

when you run the command `git status` you will see the file you edited marked in red this means that it needs to be staged or added in order to commit it to the repository. to do this you will want to run this command:

```
git add <filename>
```

Now if you run the `git status` command you will see the file marked in green meaning it is added and ready to be committed.

If you have deleted a file and are on the add step you will instead want to replace add with *rm* as this will mark it as a remove and not adding. the code would look like this:

```
git rm <filename>
```

### Commit

now that it's successfully added you need to run the commit command like this:

```
git commit -m "<Your message here>"
```

You might notice we used the *-m* argument here, this sets a message that you type in double quotes about what changes were made to these files. This is not meant to be a paragraph, simply write what has changed and save any other notes for GitHub.

### Push

Lastly, now that you have committed all changes you are going to want to push all your changes to GitHub where everyone else can see them. Right now the Files have been committed to your computer but not to the GitHub repository, so to do this you'll want to run this command:

```
git push origin main
'''
 
This command only works if you are in the main branch which most beginner projects will deal with so for now this is the only push command you'll need to know.
 
Lastly always always always remember to ACP whenever you make any changes to a file or repository.
