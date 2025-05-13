# Author : Sahil K
<br>
Basic Github commands: 

   1) git clone <link>  //to join the repo to the local computer
   2) git status           // to check the status of the files
   3) git add              // 1st step of saving code  
   4) git commit -m "info"  //finalizing the code to push at github
   5) git push origin main  // pushing the changed git file to github
              <!-- here origin refers to the name of the remote location on github we can change this name -->
              <!-- main is the branch here -->
   6) git ls                //shows all the existing files in the folder except hidden files
   7) git ls -a             // shoes all files along with hidden files
   8) cd folder_name        // to enter in a folder
   9) cd ..                 // to exit from folder
   10) git init            // to connect locally created folder to git
   11) git remote add origin main <link> //to connect local repository to the another repository created on github
   12) git remote -v        //used to verify remote directory
   13} git branch           // used to see the branch we are working on
   14) git branch -m new_name  // to rename the branch


…or create a new repository on the command line

echo "# local--repo-new" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Sahilkhodake07/local--repo-new.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/Sahilkhodake07/local--repo-new.git
git branch -M main
git push -u origin main

   // M shows modification 
   // u shows untracked file
