Hello everyone!

Please, find below a homework task.

This isn't an easy task, so if you have any difficulties feel free to postpone it and return later. Before doing the task I strongly recommend you look through the first three chapters of the Pro Git book (Getting Started, Git Basics, Git Branching). The task contains a few merge conflicts, it is done intentionally and in real life rebasing is easier.

Clone the following repo: https://github.com/SergiiPiatakov/calculator.git .
Using `rebase -i` swap the following commits: "fix truncation error" and "formatting: use tabs instead of spaces".
Then sign them and create two patches using `git format-patch`.
Then combine "improve calculation accuracy" and "fix truncation error" into one patch using `rebase -i`. Sign it.
Then remove the top patch "formatting: use tabs instead of spaces" using `git rebase -i` - I really don't like tabs ;) .

Rename the current remote on the "github". Add another remote: https://gitlab.com/SergiiPiatakov/calculator.git and call it "gitlab".
Get code from the "gitlab" remote by `git fetch`, and explore it by `git log gitlab/master`.
Then grab the commit: "add a multiplication operation" by `git cherry-pick`.
Create your own patch about 5-15 lines (any changes).
Push the result into your own repo.

Please, provide me with:
- link on your repo;
- two patches which was prepared by `git format-patch`.

In case of any difficulties don't hesitate to ask for help.

Best Regards,
Sergii.
