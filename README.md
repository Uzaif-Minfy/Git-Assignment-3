# Git-Assignment-3


## merge conflict that occurred when attempting to merge the feature/add-content branch
![image](https://github.com/user-attachments/assets/50337ab9-ddb0-4270-90a5-afe2d79a7e39)



## confirming the successful merge of the second branch
![image](https://github.com/user-attachments/assets/f8e071f2-ab76-4117-9cd2-3ee632318383)


## Explanation of how conflict was resolved
I started by creating a new GitHub repository and added a simple index.html file with basic structure.

From the main branch, I created two separate branches: 
- One for styling changes (feature/update-styling), where I added internal CSS.
- Another for adding content (feature/add-content), where I inserted a new paragraph into the body section.

Both branches modified the same HTML file, but in slightly different parts of it.

I first merged the styling branch (feature/update-styling) without any issues.

When I tried to merge the content branch (feature/add-content), GitHub flagged a merge conflict.

I manually edited the file to include both the CSS changes from the first branch and the paragraph content from the second.

After saving and marking the conflict as resolved, I committed the changes and completed the second merge.

In the end, the final index.html file included both sets of changes—styling and content—and the repository was successfully updated.
