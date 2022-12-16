 ## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
1.First, If a user wants to create a project it require many changes and to save this changes/history git is used. Noting down the history is called version control so git is a version control software. The history is saved on your local machine so git works locally.

2. What is the difference between Git and GitHub?
2.GitHub is type of social-networking site for developer if 2 0r more person are working on the project they can share the code and see each other work.Git is locally worked on system and you can only work on your code. git is open source and github is owned by microsoft.

3. Why do we create a branch?
3. To work on a github repository that is hosted centrally different people have different codes so each person need to work on the single chanel that is called branch.

4. What is the purpose of a Pull Request?
4. when you have made the changes in repository and want to show this changes to the head then to make the git pull request.


5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
5.git checkout command is used



6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
6.The git pull command first runs ‘git fetch’ which downloads the content from the specified remote repository and then immediately updates the local repo to match the content.
When we use the command git fetch, Git gathers any commit from the target branch that does not exist in our current branch and stores it in our local repository. However, it does not merge it with our current branch.
This command will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches. The git merge command takes two commit pointers, usually the branch tips, and finds a common base commit between them. Once it finds a common base commit, it will create a commit sequence.


7. What is a merge conflict?
Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. Git can often resolve differences between branches and merge them automatically.



8. How do you resolve a merge conflict?
The final option is to review each change separately. This option is also the best path to take, especially when working with multiple files and people. To make this job more manageable, use special tools to help review individual conflicts .