# Dog-Git-Practice
FEW Day 01
Practice Git and GitHub with some doggy cuteness!

Initialize a new git repo 
git init
Create a new file called [dogs.md]
touch dogs.md
Open it with VSCode
code dogs.md
Add a list of dogs with markdown syntax like the one below:
		
# List of Dogs
1. German Shepherds
2. Bulldogs
3. Samoyeds
4. Huskies
5. Pugs
6. Poodles
7. Chihuahua

Preview changes using CTRL+SHIFT+V
Add and commit the changes
git add dogs.md
git commit -m “Added a list of dogs”
Create a new branch to add a new dog
git branch new-dog
Checkout the new branch
git checkout new-dog
Add “Alaskan Malamute” to the list
Stage the changes
Commit the changes
Checkout master again to notice changes,then go back to new-dog
Look at the history of commits so far (in new-dog) 
git log 
Checkout master then merge the new branch
git checkout master
git merge new-dog
Look at the history of commits so far (master) 
git log 
While in master, add “Golden Retriever” as a new dog.
Stage the changes
Commit the changes
Checkout new-dog branch
Add a new dog “Rottweiler” 
Stage changes
Commit changes
Checkout master
Merge the new branch into master
git merge new-dog
Resolve conflicts
Look at the history of commits so far (master) 
git log 

