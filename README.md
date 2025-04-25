# Version Control System

## Introduction

This mini-project demonstrate the importance of Git as a VCS, a vital tool in Software development for collaboration, development, and version control.
How it ensures that all contributions are preserved and integrated efficiently and effectively.
Using analogy of two individuals Tom and Jerry working collaboratively on a project.

### Conceptualizing The Concept with Tom and Jerry

1. Initial Setup:
   - Both Tom and Jerry installed Git on their computers and then cloned the project _*miniproject-2*_ to their local machines. So they each have a copy of the project including the files and the version history.
   - Here, i cloned the the created project to my local machine.
   ![cloned code screenshot](img/00.gitcloneminiproj-2.png)

2. Tom and Jerry Start Working:
   - I first, created the _index.html_ file in the _main/master_ branch.
   - Added and pushed the changes to the _main/master_ branch.
    ![added index.html screenshot](img/0.gitadd-indexhtml.png)
    ![commit index.html screenshot](img/01.commit-indexhtml.png)
   - Then created and switched to the _updated-navigation-Tom_ branch
    ![updated-navigation-Tom](img/1.switch-to-tombranch.png)
   - pulled the latest changes from the central repository.
    ![git pull](img/2.gitpull.png)
   - Added the _nav bar_ section to the _*index.html*_ file and pushed the changes to the _*updated-navigation-Tom*_ branch.
    ![pushed nav-bar screenshot](img/8.upstream-tom.png)
   - Repeated the same procedure for Jerry.

3. Merging Changes:

   - After successfully pushing the updates to each branch.
   - I switch to each branch and made a Pull Request (PR) and then switch to the master branch, accepted the PRs, resolved the conflicts, and merged the changes.
  Tom PR:
   ![Tom PR](img/1.Tom-PR.png)
  Merge Jerry PR:
   ![![merge branches](img/3.merge-branches.png)](img/2.merged-jerryPR-successful.png)

### Conclusion

This project demonstrated  how teams members can work simultaneously, without overwriting each other's changes.
Git tracked their changes, allowing them to merge their updates stress-freely into the main project.
