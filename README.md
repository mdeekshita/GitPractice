This repository is made to practice the fundamentals introduced to you in the Data workshop. You must follow software best practices, and be sure to execute commands in the correct order in order to prevent changes
to the main repo. You will do the following: 

# Stage 1: Branching #
Like we mentioned in the workshop, creating your own branch from the main repository and using that as your main working area is necessary for clean and organized code. NEVER WORK DIRECTLY IN MAIN.
#### TO DO: ####
1. In the terminal, run the command: git branch [feature-yourname]
2. In order to switch into the branch, you must run the command: git checkout [feature-yourname]
3. In order to ensure that your branch was made, run the command: git branch
   
** Congratulations! You have completed Stage 1! **

# Stage 2: Editing, Committing, and Pushing #
Now that you have your own branch, you can make any edits to files in the repository. Open the file "CONTRIBUTORS.md".
#### TO DO: ####
1. Open the file "CONTRIBUTORS.md"
2. Find your name in the list and add a fun fact about yourself next to it.
3. In order to save your changes you must stage and commit your changes. Run the command: git add . & git commit -m [message], in that order
4. In order for your edit to be saved to the repo, you must push it. Run the command: git push -u origin [feature-yourname] --> the -u flag links your local branch to the remote, so later on you will only have to run git push. 

** Congratulations! You have completed Stage 2! **

# Stage 3: Pulling and Merging #
You have to make sure that you are constantly up-to-date with the current main branch, and that any changes you make can be seen by everyone else on the project. 
#### TO DO: ####
1. In order to get the latest changes, run the command: git pull origin main
2. In order to update the main branch, you must switch into the main branch. Run the command: git checkout main
3. In order to update the main branch with your feature branch, run the command: git merge [feature-yourname]
4. Finally, run the command: git push origin main
5. Check to make sure that you can see the changes by opening the "CONTRIBUTORS.md" file in main.
   
** Congratulations! You have competed Stage 3! **

# Stage 4: Create a Merge Conflict # 
Now that you have practiced running the basic commands in git, we need to practice resolving merge conflicts.
#### TO DO: ####
1. Find a partner!
2. Open the file "conflict.md"
3. Looking at the sentences available, choose a sentence you would like to edit. BEFORE editing it, please go to one of the chiefs to tell them that you and your partner have chosen that line.
4. Once you recieve confirmation from a chief, make sure to switch back into your feature branch.
5. Both you and your partner, individually, will remove the blank line in your copy of the file and will fill in the blank.
6. Save your changes locally by staging and committing, and push to your feature branch.
7. Pull the latest changes from the main, and then switch from your feature-branch to the main repo.
8. Run the command to merge into the main branch. This will cause a merge conflict.

** Congratulations! You have completed Stage 4! **

# Stage 5: Resolve the Merge Conflict #
Editing the same line in the same file is a common reason to get a merge conflict. Now, we must fix it. 
#### TO DO: ####
1. In order to determine which file is causing the conflict (right now it's easy to tell, but in a project it'll be a lot more difficult), run the command: git status
2. Open the file "conflict.md". You will see your name and your partner's name wrapped in <<< and >>> markers.
3. With your partner, choose ONE correct answer for your line, and accept that change.
4. Once the file looks correct and the markers are gone, save the file and run the command: git add contributors.md
5. Then, stage and commit by running the command: git commit -m [message]
6. Since you are already in main, there is no need to change branches. Simply run the command: git push
7. Open the file "conflict.md" to ensure that your changes were made.

** Congratulations! You have complete Stage 5! **

