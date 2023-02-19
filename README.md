run this command to tell git of the location of your git hooks (it helps with sharing hooks with other team members)
	git config core.hooksPath.githooks

commit-msg : make sure that your commit follow a certain pattern

pre-commit : make sure that you don't commit in a protected branch (main or master)

pre-push : make sure that you add a jira ticket in all of your commit messages