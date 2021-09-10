## **Revisions and the Cloud Reflection**


## **Practice with Git.**
        1. Clone down Reading-notes Repo to local computer, so i can do all future work in VS Code.
        2. Review past Reading-Note entries. (fix errors and bulk up)
        3. Build out site structure. (Home page should contain only into and Table of Contents. Create link from Table of Contents to topic's page.)
        4. Keep a clean Git history. (After Every Meaningful Change, A-C-P. Write commit messages to explain WHY you made changes.)

## **Git Tutorial: A Comprehensive Guide**

1. Version Control
        -Local (A Local VCS entails one database on your hard disk that stores changes to files.)

        -Centralized (This system entails a single server storing all changes and file versions, which can be accessed by various clients.)

        -Distributed (DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.)
2. Git       
        - Snapshots (Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.)

        - Local Operations (allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.)

        - Tracking Changes
        - Loss of Data
        - States
                - Committed (Data is securely stored in a local database.)

                - Modified (File has been changed but not committed to the database.)

                - Staged (Flagged a file’s changed version to be committed in the next snapshot.)
 


3. Setting Up a Git Repository
        - Importing
        - Cloning

4. Workflow
        - Local Repository Structure
        - Saving Changes
                - Tracked (Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.)
                - Untracked (Untracked files were not in the last snapshot and do not currently reside in the staging area.)

        - The Life Cycle of Status
        - Check File Status
        - Track and Staging a New File
                - Single File (git add filename)
                - All Files (git add *)
        - Committing a File (git commit -m "Explain")
        - Committing all changes (git commit -a)
        - Pushing Changes (git push origin master)
        - Stashing Changes (When you are not ready to commit changes but do not want to lose them either, git stash is a great option)
5. Remote Repositories
        - Cloned Repositories (As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.)

        - Seeing Your Remotes (git remote)