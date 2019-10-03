# Rename Git branch locally and remotelly

```shell
git branch -m old_branch new_branch # Rename branch locally    
git push origin :old_branch         # Delete the old branch    
git push -u origin new_branch       # Push the new branch, set local branch to track the new remote branch
```
