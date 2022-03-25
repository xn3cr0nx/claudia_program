# Rebase squash

0. Pull remote changes to be sure you are synced with remote origin
1. create a new branch from origin/main named `rebase-squash`
2. Type a funny sentence in the line below after `>>`
>>
3. Commit the change above with commit message "my funny commit"
4. Type a new funny sentence in the line below after `>>`
>>
5. Commit the change above with commit message "a new funny commit"
6. interactively rebase and apply a squash to last commit, changin first commit to "my first updated funny commit"
7. Open a new PR from `rebase-squash` to `main`
8. Ask for review to a collaborator (guess who)
9. Merge changes when approved
