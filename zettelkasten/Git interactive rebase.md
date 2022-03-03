02/03/2022 16:28:02

Status: #🌱

Tags: [[Git]]

# Git interactive rebase 

When you create a repository and start to commit it you are telling a history. Analyzing your commit history you can know everything that already happened in your repository. Every new commit created is a new chapter of your repository story.

`git rebase` is like a time machine. Using the rebase command you can go back to a given commit and rewrite your repository story.

This is a simplistic explanation. With git rebase you can do so much more than edit or delete commits.

The command for it is:

	git rebase -i
	
The workflow is:

	git log
	
	git rebase -i HEAD~X [X being the number of commits you want to edit]
	
Then in your editor of choice a file with the selected commits will be shown. There will be a bunch of options to do as you please with your commits. When you save and close this file a new file will popup, there you can do your edits.

---

# References

https://www.youtube.com/watch?v=0MVXlGQe9nU
