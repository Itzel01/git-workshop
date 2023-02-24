# Git-Workshop

## Lesson Overview:
### Agenda

- 00:00 - 10:00: Review git concepts 
- 10:00 - 40:00: Git Workflow 
- 40:00 - 60:00: Demo

### Objectives:

Fellows will be able to: 
- create branches to seperate feature work 
- merge branches locally 
- get rid of merge conflicts locally
- create pull requests 
- merge braches into the main branch 
- always have an updated and functional main branch 

### Vocabulary 

- branch 
- merge 
- pull request 

### Rewiew: Branching 

<details> 
  <summary> When should we create a new branch? </summary>
  
  Branches are used to diverge from the main code base. They are useful because they create a copy of existing code 
  without modifying the existing code. Think of it as your very own sandbox where you can create anything new. 
  Therefore, a new branch should be created for any new change to any of the files in the project. 
  This includes but is not limited to creating a new feature in the repo and/or fixing a bug in the repo. 
  
</details>

<details> 
  <summary> Useful Commands for branching </summary>
  
   - `git branch <branchName>` 
      - This command will create a new branch with the branch name provided.   
   - `git branch` 
      - This command is useful in seeing which branch you are currently in.
   - `git checkout <branchName>`
      - This command is used to change from one branch to another.
   - `git checkout -b <branchName>`
      - This branch is used when you want to create a new branch and change into that branch at the same time.
    
</details>
    
### Git Workflow

Merge conflicts occur when we have code that could possibly overwrite code that was already there. 
They are bound to happen if multiple people are working on the same pages. 
The main branch should always have working code so as a best practice, we shouldn't 
- work off of our main branch. 
- Merge into our main branch code that hasn't been tested. 

Here are some steps that we can take in order to avoid merge conflicts or bugs in the main branch.

1. Create a new branch for new branch 
2. Constantly stage and push up code for that branch, this will not conflict with the main branch 
3. When done with the feature, checkout to main 
4. Pull down changes from main 
5. Checkout to branch you were working off of 
6. Merge the **main** branch into your branch
7. Fix merge conflicts if any 
8. Push up changes to branch 
9. On github's GUI, start a pull request 
10. Communicate to team that a feature is done and in need of testing 
11. Team member(s) should test new feature by locally checking out to the remote branch 
12. Team member should approve Pull Request if it is working 

### Additional Resources: 
Slide Deck Link
