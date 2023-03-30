## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
~ Git is known as a version control system, in other words, it has the duties and abilities to manage and track changes you've made or are making to code.
2. What is the difference between Git and GitHub?
~GitHub is tha place with which we will store data that we've changed using Git. This is typically done with the intention that we would be collaborating with other developers on one peice of code.
3. Why do we create a branch?
~We create branches in the interest of preserving the integrity of the main branch should something horrible happen. Like, should there be some major bug due to a feature added or a change made, it makes things significantly easier to check the history of the branches to see which one is causing the issues.
4. What is the purpose of a Pull Request?
A pull request is the starting point for inputting the code you had just changed into the main branch. Pull request are, in a way, presenting everything you've done so far to your lead or colleagues and asking them to review it. Once review is complete, and there is no noticable bugs or issues, it will be combined with the main branch.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
Given the provided circumstance, I would type 'git checkout main'.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch will download other commits and files from a repository for you to peruse, typically to see what changes have been made. Git merge will take the files you 'fetched', otherwise known as multiple commits, and merge them together into one history. Git pull executes the same way as Git fetch, but this time, it will automatically execute git merge as well.
7. What is a merge conflict?
A merge conflict is something that happens when two people make changes to the same line/file. Also, it could be a line you changing/working on was deleted in someone elses commit. This would create a merge conflict.
8. How do you resolve a merge conflict?
In order to resolve a merge conflict, theres a few methods. First, you'd find the trouble maker in your text editor(eg nano or VSCode) and decide whether you want to keep your change, the other parties change, or resolve to making a new commit. To find the issue, it will be highlighted with these indicators ; <<<<< HEAD ======= >>>>>>> branch-a. Make sure to delete this indicators after making the change.
