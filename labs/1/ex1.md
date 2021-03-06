# Astro 585 Lab 1, Exercise 1

# Setup/Learn to use git for getting/submitting assignments.

Instructions for Setting up git to get and submit labs/homework assignments:

1.  Create an account at github.com. Note that you're encouraged to use a "code name", so that we can discuss your code and have peers review your code, without having to reveal your true identity. Also, note that you're welcome to use an alternative git server if you prefer (e.g. to keep your repositories private), just let the instructor know how to access your repository.
2.  Setup up git on your machine. The astro computers and Osmond lab should already have git installed. However, you will need to setup each system to authetnticate with GitHub using either HTTPS or SSH. You may want to follow the instructions at [setup git for linux](https://help.github.com/articles/set-up-git/#platform-linux). While there are GUIs for Mac and Windows, the command line interface described in the Linux section should work for Mac users or people using Windows and cygwin on their personal laptop. Also, remember that you shouldn't use your real name and email if you want to preserve your anonymity.
3.  Send the instructor an email with your username, so you can be added to the team that can access the class repository.
4.  Follow the instructions on [forking a repository](https://help.github.com/articles/fork-a-repo/) using the [PsuAstro585 template repository](https://github.com/eford/PsuAstro585) and cloning it on your local machine.
5.  Test submitting a file.  (This is analogous to what you'll do for each of your subsequent assignments.)
  * Change into the directory for the course repository on your local machine.
  * Make sure you have the most recent version of the template files, instructions, etc. by running `git pull` )
  * Create a simple text file in the lab/0 subdirectory of your local repository.  (e.g. `echo "Hello World" > lab/0/code_name.txt` ).  Note this is the step that you'd replace with the code development and experimentation for any other exercise.   
  * Stage the changed file(s) to be commited your local repository.  E.g., 
```git add lab/0/code_name.txt; ``` 
  * Commit the staged file(s) to your local repository.  E.g., 
```git commit -m "my test at commiting a file"``` 
  * Push the changes to your fork of the class branch.  
```git push```
  * Then go to your repository's webpage on github.com (or git server of yoru choice) to verify that the file you added showed up. If you see it, then congrats... you're using distributed version control system.  If not, ask someone for help.
  * If you're using github.com, then when you're ready for the instructor to review your work, [create a pull request](https://help.github.com/articles/creating-a-pull-request/) for your changes to be merged into the course's template repository.  (Otherwise, just email me with the url for your repository.)  


If you'd like to learn more about how to use git to make your work more efficient, [try reading some of these resources](https://help.github.com/articles/good-resources-for-learning-git-and-github/).  And let me know which you found to be most useful.


