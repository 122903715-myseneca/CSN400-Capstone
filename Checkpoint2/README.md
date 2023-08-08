# Checkpoint 2 Submission

**COURSE INFORMATION: NDD**
**STUDENT'S NAME: Aleksander Savotchka**
**STUDENT'S NUMBER: 115894214**
**GITHUB USER ID: 122903715**
**TEACHER'S NAME: Atoosa Nasiri**

### Table of Contents
1. [Part A - Adding Files - Local Repo Workflow](#header1)
2. [Part B - Inspecting Local Repo with `git status` and `git log`](#header2)
3. [Part C - Creating & Merging Branches](#header3)
4. [Part D - Git Branching Strategy Review Question](#header4)

### Part A
```
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   Checkpoint2/README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	git_status_uncomitted.txt
	git_status_untracked.txt

no changes added to commit (use "git add" and/or "git commit -a")
```
## Part B
"Git Status," is used to show the current state of the working directory. It provides information such as which files have been modified, added or deleted since the last commit. The Git Status output includes: Untracked files, changes that are not staged for commit and changes that must be committed. Git Log however, is used to display the history of commits in the repository. It shows a list of commits, which start from the most recent commit, and going backwards.

## Part C
```
commit 87b763dc587c0b7012aaf6715e4f43eafff85441
Author: Alex Local VSCode <asavotchka@myseneca.ca>
Date:   Mon May 15 13:55:33 2023 -0400
```

## Part D
1. **What are the differences between develop branch and main branch?**

The main branch is typically considered to be the primary branch of the repository, whereas the "develop," branch is mainly used for ongoing devlopment work. When we commit to the main branch, the files are expected to be production-ready and tested. The main branch is where we commit our finished work mainly.

2. **What are the three supporting branches? Briefly describe the function of each of these supporting branches.**

There are three types of supporting branches:
- Feature Branches: Feature branches are used to develop new features for projects. Many developers will create branches off the development branch to develop and test new features in.

- Release Branches: Release branches are mainly used to prepare stable versions of software ready to release. 

- Hotfix Branches: Hotfix branches are mainly used for troubleshooting and to address critical issues in the current release.

3. **What are the best practices in working with release branches?**

- Create release branches from develop branch: This ensures that the features that are intended for release are included, and development on the develop branch remains unaffected.

- No new features on release branches: In the release branch, only include bug fixes, document updates, and other adjustments. Also, avoid adding new features to the release branch to minimize the risk of new issues occuring.

- Merging into main and develop: Once the branch is ready, we merge it into both the main branch (for creation and release) and the develop branch(to edit bug fixes later on and improve throughout ongoing development)








