# Coding-Discussion-01

## Instructions 

For this discussion, please do the following: 

- Clone the Github repository 'https://github.com/PPOL564-Foundations-Fall-2018/Coding-Discussion-01.git' from our Github 'PPOL564 - Fall 2018' organization account. 
- Generate an original text file using the commandline (e.g. `echo` or the like). Name the file using last-name as the file head: e.g. 'dunford.txt'
- In the file, write your full name and a brief sentence regard one thing new you learned in class yesterday that you did not previously know. 
- Stage the file and then commit using your name in the message: i.e. "Adding Eric Dunford's text file"
- Push the file to the class repository. 
	+ Note that you need to ensure that the repository is up-to-date. If the current version of the repo is "ahead" (i.e. someone already made a change prior to you), then you'll get an error in your console telling you that you need to pull the repo once again to update. 
	+ If this is the case, use `git fetch` which will pull all the new data as a separate branch, and then use `git merge -m "merging paths"` to bring those two branches together. 
		- Note that if you `git pull` rather than `git fetch` the merge will occur automatically and you'll need to follow a few text prompts in your commandline that can admittedly be a little confusing to execute. 
	+ Once you've done this, you can `git push` the current version to the Github remote.
- Finally, make sure your new file appears in the repository (just check online, you should see it added to the repo).

## Response

Respond to someones post by Sunday. The response need not be anything more than your name, e.g. `Eric Dunford`. Place this under the original author's commentary. Again, you'll need to pull the latest version of the repository, update a file locally and then push the changes you need to make. 

In this, we will have done three things: (1) interacted and mutually collaborated on a mock "project", (2) downloaded a repository, edited it locally, and then pushed it back to the remote, (3) dealt with some basic version conflict errors. 

Commands you'll want to keep in mind:

`git fetch`: Pull the current state of the repository (data only)
`git pull`: Pull the current state of the repository (automatically merges)
`git add`: Stage local changes.
`git commit -m "some message"`: commit local changes.
`git merge -m "some message"`: merge different branches of a repository (important when there is a conflict)
`git push`: push your local version to Github.
