# Creating a new note

To create a new note select the `+` in the menu. Give it a name, and optionally define its path in the repo, and some associated labels.

After you have made the modification you should see a red symbol on the commit menu button. This indicates that changes have been staged for commit. You neither have write access to the repository nor do you have configured GitHub authentication yet, so you will not really be able to commit anything. Also, don't expect very good error handling just yet if you try ;). However you should get the idea: If you setup GitHub authentication and have write access to a repo, commiting your changes would basically be one mouse click away.

# State reset / discarding changes

If you want to go back to a state identical to the remote, i.e., discard all changes, you can click the reload button in the menu. If you have any uncommited changes it will ask if it is okay to discard your changes. If you do so, you get a fresh snapshot of the remote repository.
