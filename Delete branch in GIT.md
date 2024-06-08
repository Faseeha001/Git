# Delete a Git Branch #
## Deleting a Git branch can be done either locally or remotely. Follow these steps to delete a branch safely ##

## Deleting a Local Branch
Step 1 : List All Branches
List all the branches to ensure you are deleting the correct one.
To delete master branch 
**git branch**
![image](https://github.com/Faseeha001/Git/assets/169563689/114b9bf8-1f4b-455b-93cc-a9a434c78c43)

Git Hub : 
![image](https://github.com/Faseeha001/Git/assets/169563689/1f8f5a85-893e-49d0-823a-0402b7e786c6)

Step 2: Switch to a Different Branch

You cannot delete the branch you are currently on. Switch to another branch first.
Delete the Branch Locally:

First, ensure that you're not currently on the branch you want to delete. If you are, switch to a different branch. Then, delete the branch locally:

switch to main branch before deleting master branch
**git checkout main**
or
**git switch main**
![image](https://github.com/Faseeha001/Git/assets/169563689/d9f6e677-5613-45c1-88b2-933870154af2)

Step 3: Delete the Local Branch

Use the following command to delete the local branch.

**git branch -d branch_name**
Replace branch_name with the name of the branch you want to delete.

The -d option will delete the branch only if it has been fully merged.

If you want to force delete the branch, use:

git branch -D branch_name
![image](https://github.com/Faseeha001/Git/assets/169563689/2da62838-5b00-4d86-8cb7-6c4332e37a31)

push the changes to origin to delete branch from Git hub Repo

![image](https://github.com/Faseeha001/Git/assets/169563689/f984876c-1b92-4e40-ac1c-a7d267ca4f0b)
Git Hub :

![image](https://github.com/Faseeha001/Git/assets/169563689/311a280f-bb35-4da7-a7f9-826112aff4cb)
