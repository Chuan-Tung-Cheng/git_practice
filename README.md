# Git_practice

# Goal : 
1. Help users know git commands like "Clone", "Add", "Commit", "Push", "Pull", "Branch", "Merge", "Delete Branch"
2. Clarify how to use each command based on specific scenarios

# Term Explanation :

1. Clone : Pull the determined repository from GitHub 
    * Scenario : Users download the repository first time when they initially access to it
    * How it works : Device will download from GitHub (remote location) to our own computers (local location)


2. Add : Add the altered files into staging area once files are altered
    * Scenario : Users add the altered files into staging area before committing the entire stage    
    * How it works : Device will add the altered files into staging area
    * Remark : If users don't want to add the altered files, users can use "discard" to abandon the changed part


3. Commit : Complete the entire stage where users have added the files into staging area and transfer it into Git's repository of users' computers
    * Scenario : When users have confirmed all the added files in staging area is correct, users can commit what they've done, which means users have saved all the altered files into Git's repository of users' computers.
    * How it works : Device will transfer the cache that is created by adding phase into repository
    * Remark : Once completing commit, that means users have consented all the changes to the files. Users are not recommended to go back to the last version for realtering and commiting again, which easily gets your collaborators confused with which branches are the right on to go

4. Push : Sync what users have commited into cloud platform, such as GitHub, GitLab, and so on

# Git Clone syntax:
1. git clone <--depth 1 [optional]>  <GitHub_repository_website> <file_name [optional]> :
   * It means all files in the main and the branches and the records of commitment will be downloaded.
   * We can enter git branch -a on CLI to check what branches this repository has
   * If users want to rename the directory, they can enter the expected name into file_name
   * If users just want to do CI/CT, you can add '--depth 1' before the website, which will allow you to download the latest version without any records beforehand

2. git clone -b <branch_name> <--depth 1> [optional] <GitHub_repository_website> <file_name [optional]>:
   * It means only the selected branch and the records of the branch will be downloaded
   * If users want to rename the directory, they can enter the expected name into file_name
   * If users just want to do CI/CT, you can add '--depth 1' before the website, which will allow you to download the latest version without any records beforehand

