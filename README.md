# Git_practice

# Goal : 
1. Practice git commands like "Clone", "Add", "Commit", "Push", "Pull", "Branch", "Merge", "Delete Branch"
2. Clarify how to use each commands based on specific scenarios

# Command :

* Clone : Pull the determined repository from GitHub 
    * Scenario : Users download the repository first time when they initially access to it
    * How it works : Device will download from GitHub (remote location) to our own computers (local location)

* Add : Add the altered files into staging area(暫存區) once files are altered
    * Scenario : Users add the altered files into staging area before committing the entire stage    
    * How it works : Device will add the altered files into staging area
    * Remark : If users don't want to add the altered files, users can use "discard" to abandon the changed part

* Commit : Complete the entire stage where users have added the files into staging area and transfer it into Git's repository of users' computers
    * Scenario : When users have confirmed all the added files in staging area is correct, users can commit what they've done, which means users have saved all the altered files into Git's repository of users' computers.
    * How it works : Device will transfer the cache that is created by adding phase into repository
    * Remark : Once completing commit, that means users have consented all the changes to the files. Users are not recommended to go back to the last version for realtering and commiting again, which easily gets your collaborators confused with which branches are the right on to go 



