# Practicing Git commands

# The U in the file name is for Untracked file. It means any changes in the file will not be tracked. To track the file use the command git add <filename>

# After the git add command the U will become A, so the file is added and will be tracked

# We can also remove the file using the command git rm --cached <file name>

# We will use git commit command to create a staging enviromnet which is a temporary env whose files are pushed to github (git commit -m "any message" )

# Now rename the branch name to main. Writing main is not compulsory , we can also write master, but most of the developers makes main branch initially (git branch -M main)
# Now we will commit  in this main branch and push the code to the github repository.

# Next step is to give the indication of destination (URL of repository in which the code has to be pushed) (git remote add origin <link>)

# Final step is to push the code from main (local branch) to the origin(github)

# It is also important to give the user name and email when starting fo rthe first time
# (git config --global user.name "Chinmay-2704")
# (git config --global user.email "narayan270403@gmail.com")

# Use git add . (to add all the files at once)

# Its done. Hurrayyyyy