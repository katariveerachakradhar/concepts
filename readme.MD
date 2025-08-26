#Git --- Version control 
		1.0,1.1,1.2 ...... ---> It will handle
		
		
Pull request and approval and conflicts and finally pushing the dosa types to Git

#Git Reset : ---> Reset the changes back
					|		|		|
				Soft 		Mixed 	Hard
			
			*Soft ---> git reset --soft<commit_id>
			*Mixed ---> git reset --mixed<commit_id>
			*Hard ---> git reset --hard<commit_id>
			
		Workspace ---> staging area ---> local repo ---> remote repo
		
		*Soft ---> local repo <---> satging repo
		*Mixed ---> local repo <---> workspace
		*Hard ---> Max we won't use because of date loss and uncommited changes.
		
#Git reset/revert :
		reset ---> Undo the changes before you commit to remote
		revert ---> undo the changes you already commited
		
		git reset --soft HEAD~1 ---> It will make changes to one step
		git reset --mixed HEAD~2
		git reset --hard HEAD~3
		

#Git squash :
		--> Used to combine multiple commits into a single
		--> History cache less
		--> Branch merging
		--> Interactive rebase ---> git rebase -i HEAD~N N=1,2,3....

#Git stash :
		--> Temporarily save uncomitted changes in your workking directory 
		-->Switching branches or perform other tasks without committing incomplete works.
				--> Saving changes
				--> Viewing stashes
				--> Applying stashes
				--> Managing stashes
				
#Git Cherry-pick : 
		---> To selected one we can apply
		---> Applying Hotfixes
		---> Copying specific features
		---> Recovering lost commits
		
		git checkout <target-branch>
		git cherrypick <commit-hash> ............

	git log --oneline ---> To display log in single line.
