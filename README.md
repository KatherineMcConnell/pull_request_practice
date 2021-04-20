# pull_request_practice

### Practice
 * Check out a new branch
 * Make some additional changes to your README
 * Commit those changes
 * Visit GitHub
 * Create a pull request
 * Merge your pull request
 * Check out your main branch locally
 * Pull your changes into your main branch

### Git Workflow with Branching and Pull Requests

 This is the final version of our workflow, and is what you should be doing on every project, partner or solo.

 * git status - make sure our working directory is clean. If there are changes, we need to figure out what to do with them, either commit them or stash them.

 * git pull origin main - Make sure you are up to date with the latest version of main.
 git branch <feature name> - make a new branch based on a feature you want to add. Alternatively, you can use git checkout -b <feature name> to create and checkout the branch in one command.

 * git checkout <feature name> - Checkout the branch

 * Make changes

 * git status - we should see the files we changed as unstaged.

 * git add <name of file we changed> - stage those changes for commit. We need to do this for each file we changed.

 * git status - we should see the files we changed as staged for commit.

 * git commit -m "short message about the changes we made" - commit the changes.

 * git push origin <feature name> - Push your branch to Github.

 * Repeat steps 4 - 10 until the feature is complete

 * Put in a Pull Request (PR) to merge your branch into main.

 * Visit GitHub and merge your pull request into main.

 * git checkout main - Switch back to the main branch.

 * git pull origin main - Make sure that you have the most recent changes that you made on your local main branch.
