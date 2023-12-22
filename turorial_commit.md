# Tutorial for creating pull request

## How to undo a commit?

Click `History` to see the log of your committing. Right click the commit that you want to undo, and then choose `revert this commit`. This will create a new commit in the `History`. Then you can right click this reverted commit and choose undo. After this, you will find that this reverted commit will come bach to your changes list.

## What is the differences among to stage, commit and publish

- To stage means that you restore your changes in a file into staging area, which means that these changes are included in the next commit. Now the files in your local repository is not changed.

- To commit means that you commit the changes in the staging area to your local repository. Now the files in your local repository is changed.

- To publish means you update the changes in your local repository to your remote repository in GitHub.

- To create pull request means that you add a pull request in the request list. This request is to tell the reviewer of this repository that you want to merge the changes in you remote repository into here.

**Note:** in the GitHub Desktop, there is no step called "stage" because the stage are combined with commit in Desktop.

## How to switch to another branch?

When you want to switch to another branch, please remember to commit your changes or them will be discarded.

When you found that you makes changes in a wrong branch, you can just create a new branch, and then there will be a popup window saying that if you want to move these changes into your new branch or you just want to discard(leave) them. Of course, you will choose the former.
