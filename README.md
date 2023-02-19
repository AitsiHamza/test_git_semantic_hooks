run this command to tell git of the location of your git hooks (it helps with sharing hooks with other team members)
	git config core.hooksPath.githooks

remove .sample extention if you want to use them
sources : https://betterprogramming.pub/enforce-your-teams-code-style-with-git-hooks-a892e584482b
	https://www.youtube.com/watch?v=-_kW5E4gGHA
commit-msg : make sure that your commit follow a certain pattern

pre-commit : make sure that you don't commit in a protected branch (main or master)

pre-push : make sure that you add a jira ticket in all of your commit messages