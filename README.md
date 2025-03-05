# practice-git

## Purpose
Practice using git to contribute to GitHub projects (without fear of messing something up :) )

### How to use this repo (based on [this article](https://www.freecodecamp.org/news/a-simple-git-guide-and-cheat-sheet-for-open-source-contributors/))
1. **Get git**: 
This article assumes you already know the steps to take to contribute to open source. If you don’t know, you may want to read [this article written by Maryna](https://rubygarage.org/blog/how-contribute-to-open-source-projects). This piece also assumes that you’ve already setup Git on your PC. If you haven’t, you may want to check the setting up Git [section of this article and do that first](https://help.github.com/en/articles/set-up-git).

2. **Clone the project to your local machine**:This is the simplest part of Git. 
  - Click the green `Code` button above, click the HTTPS link, and copy the link.  
  - Initiate a command in your favortite IDE (interactive development environment) to `clone` the respository using the link you just copied.  Alternatively you can execute this command in the git bash prompt: ` git clone <the link you copied> `

3. **Create your branch**: a branch is your personal working snapshop of the repository.  We base all our new branches from dev, so make sure you are creating your branch from the latest commit in dev.  To do this from git bash: `git checkout -b dev/<your-branch-name>`

4. **Make sure everything is good**: Issue a `git status`.  You should see that you are currenly on your branch and your `Working tree is clean`

5.  **Make your changes**: change the files you need to change.  These changes are equivalent to developing a feature.  For this "feature", your requirements are as follows:
  - add a new file that contains your biography.  You must have a link to ALL_BIOS.md at the end of your biography
  - add a link to ALL_BIOS.md with your name and the link to your new bio file
  
6. **Test your solution on your local machine**: Make sure everything is working in your local environment

7. **Stage and commit your contributions** 
  - `git add -A .` will stage all your changed files
  - `git commit -m "Your Message"` will create a commit (new snapshot) to your local repo with all the changes you made.  "Your message" should briefly describe the changes you made.  For example: "Created John's awesome biography"
  
8. **Ask to contribute to the repo**:  You are about to release something awesome to the world.  Use your GitHub account to register yourself as a contributor.  (intrusctions TBD).

9. **Pull the latest changes**: A pull is a fetch plus merge (or rebase) from the remote repo.  issue a `git pull` command to make sure you have everyone's latests stuff.  This is a great practice to reduce the chances of merge conflicts (more on this later)

10. **Push your new branch to the remote repo**: 
  - issue a `git push`.  
  - naviate to the GitHub repo (link from step 2)
  - click the branches dropdown.  Your new branch should be in the list
  
11. **Issue a pull request**  From the main GitHub screen, click the Pull Requests button and click `New Pull Request`.  Set the `base: ` value to dev, and set `compare:` to your new branch.  Then click `Create Pull Request`.

12. **Participate in your peer review**:  Reviewers will get a notification that you initiated a Pull Request.  Your reviewer will look at your changes where they can accept, reject, or leave comments for you.  When the reviewer has approved your PR, then they will issue a merge commit to merge your changes with everything in dev.

### Congratulations!  You now know the basics of contributing to a GitHub project!
![outta sight](https://i.pinimg.com/736x/80/1c/ed/801ced6421c33f3316e74d40c0636462--gary-coleman-knight-rider.jpg)
