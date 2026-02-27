The steps you took to create and manage branches.

Firstly, I  created an empty repository in my local project folder using git init command. This helped me to initializing an empty Git repository. After initializing and setting up my local environment, I cloned the remote repository from my github account using git clone command in my local system.
Next, I started creating branches starting with creating new branch for feature/header using command git checkout -b feature/header
this command  switched me to a new branch so that I can make changes in the index.html file like adding the html structure. 
After that I saved my changes and add it to staging using git add command and then committed the changes with a message related to the work.

Afterwards, I created a new branch for main using git checkout -b main. Now I have two Braches set up "feature/header" and "main" . Both branches were independent and were working separately. I checked the status of my work using git status time to time and also ran git log command to verify my work before running into major issues.Checking which branch I am using command git branch was also helpfull to know which branch  I was working on.

Now I moved to next task of creating a new branch called feature/footer for implementing the feature of adding footer section to create conflict while merge. I used  checkout command and added footer section in index.html page. After adding the footer section and saving my changes, I put the changes in staging area  using  git add  index.html and committed it with meaningful message.
This way I had three separate branches created and work was done independently without effecting each other.


How you handled the merge conflict.


 I first created a scenario to handle merge conflict where I merged my feature/footer branch into the main branch. As this was my first merge and the footer changes were not already there in the code, it did not created any issues and completed without  showing merge conflict as give in the assignment.
 After this the real situation of potential conflict was seen  where I created situation that  generated conflict for me to resolve  by making some modifications in different branch on the same lines of code . I moved to the feature/header branch and added a footer section with a different paragraph in the same line where changes already there. This caused me  creating  a conflict when I was trying to merge it  the main branch.

When this merge conflict happened while trying to merge it gave me a message saying conflict is there in the branch and highlighted the  sections that was conflicting  in the index.html file. In VS Code I was able to see the conflict and option to resolve them, It gave me an option like I want to keep both changes , keep the incoming one etc.

I decided to keep the new changes in order to resolve the conflict. After that I put the resolved file in staging using git command "git add" and then I committed my latest changes with the meaningful message like "resolving conflict" in the branch.
This commit helped me to complete my merge which was stuck due to conflict. Now my merge was completed successfully.

Lastly I pushed my updated changes in the git hub by using command git push. I learnt that we can run into conflicts and  need to resolve them before pushing it to remote repository.

