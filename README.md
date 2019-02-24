# How to use git tutorial

* You can create a **branch** whenever you want to start a new feature of a project.
  * **Branch** - A branch is essentially different versions of the project. The best way is to make each branch a feature or a task. You are branching out from the original code base.
![picture alt](https://raw.githubusercontent.com/mohamedshabarek/boilerProject/jasonGitTutorial1/img/newbranch.PNG)

* Then when you're ready to combine the work you did with the work of others you can **pull** the other person's work into your branch.
  * **Pull** -  you are grabbing the code from a certain branch and inserting it to the branch you are currently on.

* The branch that you pull from can either be from your own local branch or a **remote branch**.
  * **Remote** - A remote is a common repository that all team members use to exchange their changes. It is usually stored on a code hosting service such as GitHub. Different than a local branch because a only the local user can see the local branches. 

* If the branch is remote you can use **fetch** instead of pull.
  * **Fetch** - downloads commits, files, and refs from a remote repository into your local repository. Safer than using pull.

* When you pull/fetch the work from another branch you will in turn have a **merge conflict**.
  * **Merge Conflict** - A merge conflict is when you're trying to merge two branches that have competing commits and git needs you to decide the final changes to the merge.

* Once you resolve that merge conflict, then you will officially **merge** the work from the branch that you pulled into your current branch.
  * **Merge** - You are essentially taking the contents of one branch and putting it together with the contents of another branch.

* You can continuosly continue this process until you are complete with your project.

* Once you have your final work , you should merge it all into the **master branch**.
