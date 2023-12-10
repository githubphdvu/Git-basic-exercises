1. Create folder *learn_git_again*:  `mkdir learn_git_again`
2. *cd* into the *learn_git_again* folder: `cd learn_git_again`
3. Create file *third.txt*: `touch third.txt`
4. Initialize empty git repo in *learn_git_again* folder: `git init`
5. Add *third.txt* to staging area: `git add third.txt`
6. Commit with message *adding third.txt*: `git commit -m “adding third.txt”`
7. Check out your commit: `git log`
8. Create file *fourth.txt*: `touch fourth.txt`
9. Add *fourth.txt* to staging area: `git add fourth.txt`
10. Commit with message *adding fourth.txt*: `git commit -m “adding fourth.txt”`
11. Remove *third.txt* file: `rm third.txt`
12. Add this change to staging area: `git add third.txt`
13. Commit with message *removing third.txt*: `git commit -m “removing third.txt”`
14. Check out your commits: `git log`
15. Change your global setting to *core.pager="cat"*: `git config --global core.pager “cat”` (https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)
16. List all *git* global configurations on your machine: `git config --global --list`
17. `git config` for more options
