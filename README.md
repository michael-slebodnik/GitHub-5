LOCAL

# GitHub-5

Create a new repo on GitHub, by checking "Initialize this repository with a README".
Also in GitHub, write a few lines of text in the README.md file.
Clone the repo.
In remote (on GitHub), write "REMOTE" on the first line of the README.md and make a commit for this change.
Locally (on your computer), in your favorite editor, also change the first line of the README.md (write "LOCAL") and commit to the change.
In your Terminal, do a git pull. A nice little conflict will appear!
Reopen your editor, resolve the conflict in the README.md (choose to keep "LOCAL") and make a commit for this change.
Do a git pull again, Git will tell you you're already up to date. The conflict is settled!
Send your changes to the remote by doing a git push origin main.
In GitHub, open the README.md and make sure "LOCAL" is now on the first line. Well done!
Copy the contents of your Terminal from your first git pull (step 6 of these instructions) to the end and paste it in the quest solution
