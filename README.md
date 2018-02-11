# ARE 212 Problem Set #2

## February 2018

## What is it
The second problem set for ARE 212.

## How do I use it
Clone the repo from github.com and open in R-studio! This can be done on the command line or directly in R-studio with the url from github.com.  

### Basic workflow for version control
In your directory, **check for updates** in remote repository using:

	git fetch

if changes have been commited by others, then your local repo will be behind. Use:

	git pull

to **update your local master**, before beginning to work on the code. 

When you've finished working for the day and want to commit your changes use:

	git status

to see which files have been changed. Note: you can also use *git diff* to see exactly what has changed in those files.

Then **add** those files: 

	git add .

Then **commit** with a message explaining progress

	git commit -m "your message here"

Finally, **push your local commits** to the remote repository on github

	git push origin master

Here *origin* is the default nickname for the remote repo on github.com, and *master* is the name of the main branch we're working on. More on branches to come below!


### Branch stuff

Mostly we'll be working on the main branch, called 'master'. Sometimes though, we may want to experiment with some code and save that to a separate branch before commiting and merging that with the main 'master' code. 

To check which branch you're on use:

	git branch

To switch to a new branch use:

	git checkout -b newbranch

where 'newbranch' is the name of the new branch. 

Note: *git checkout* will create a new branch with the supplied name if none exists yet. You can also use *git checkout* to switch to an existing branch, like master. 







