1.If you want to push your code for review and merge first make new branch and then add ,Commands are as follows :

       1.git init -initializes your git repository

       2.git remote add origin  -useful for creating locol copy  of central repository while we do clone        

       3.git checkout -b new branch name -to create new branch
         git checkout  branch name       -to change a branch

       4.git add .

       5.git commit -m "write any msg"

       6.git push 
   
2.Click on compare and pull to add reviewers 

3.To clone main branch 

      1.Go to the path from cmd 
   
      2.git clone git-branch URL(http key)
   
      3.open folder in vs code 
   
      4.npm install
   
      5.nvm use node version -to switch differnt node versions
   
      6.git pull origin -to add changes in cloned repository

4. to clone sub-branch 
       1. git init 
       2. git branch -a      // it will show all the branches
       3. git remote show origin   
       4. git clone --branch <branchname> --single-branch <remote-repo-url>    //git clone --branch Two-pages https://github.com/Recruit-Plus/Recruit-plus-UI.git
