# Test_023
This project is part of a benchmark / test suite used to check the different git histories created through different development processes. The test suite is meant to be processed by SPHA-Code-Integrity.

## Textual Description
Expected Commits against integrity rules :
* Commits Updating The Readme file.
* Commit After Creating The PR.

## Changes Made In This Repo

* Create a Repo with a main branch and make an Initial Commit On The Main Branch.
* Then make a commit on the main branch updating the readme file and a file conflicting with another branch.
* Then create a new branch and make a commit on that branch that conflicts with the main branch using a new user.
* Create a PR to merge the branch with the main branch using the new user.
* Create another commit on the main branch using the other (not new) user
* Using the person who created the main branch, merge the PR using the rebase option.
* Create a new branch to create expected results file and merge the branch with the main using a PR.
