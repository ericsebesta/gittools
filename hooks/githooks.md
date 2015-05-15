# Git Hooks

These hooks can be used to automate enforcement of specific rules.

##commit-msg
This hook evaluates to validate a commit message before submission. We will validate the following rules:

1. Line 1 <= 50 characters long
2. Line 1 starts with not an uppercase letter (number is fine)
3. Line 2 is blank if it exists
4. All further lines are no longer than 72 characters long

Goals of these rules are covered [here](http://addamhardy.com/blog/2013/06/05/good-commit-messages-and-enforcing-them-with-git-hooks/) and [here](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).



