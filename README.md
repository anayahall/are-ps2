# ARE 212 Problem Set #2

## February 2018

## What is it
ARE problem set 2 is the second problem set for ARE 212.

## How do I use it
Clone the repo and open in R-studio! 

### Basic workflow
In your directory, check for updates in remote repository using:

	git fetch

if changes have been commited, use:

	git pull

before beginning to work on local updates to the code. 

When you've finished working for the day and want to commit your changes use:

	git status

to see which files have been changed. *Note: you can also use git diff to see exactly what has changed in those files.*

Then add those files: 

	git add .

Then commit with a message explaining progress

	git commit -m "your message here"

Finally, push your local commits to the remote repository on github

	git push origin master

where origin is the default nickname for the remote repo on github.com, and master is the name of the main branch we're working on. More on branches to come below!