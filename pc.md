## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

1. Git is version control system that lets you keep track of your source code history
2. Git is installed locally on your system and GitHub is a cloud-based service for Git repositories
3. So you can create changes without affecting the main line
4. So you can communitcate changes you've made to a branch in a repository on GitHub it is also the intiation process of intergrating new code into the main project
5. checkout
6. git fetch tells your local git to check and see if any changes are available in the remote repo. git pull brings the changes from the remote repository. git merge combines to branches into one
7. Its what happens when your merging branches have competing commits like both branches are trying to change some part of the same file.
8. First you understand what caused the merge conflict. Then you can edit the file so they work and once you fix the section(s) you can use git add on the conflicting file(s) and then git commit to finish the merge.