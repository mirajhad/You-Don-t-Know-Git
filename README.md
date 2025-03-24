# You-Don-t-Know-Git

1. Git to discard uncommitted changes in your working directory

```
git restore .

```
2. Moves the last commit back to the staging area (index), keeping all changes.

```
git reset --soft HEAD~

```
3. Moves the last commit back to the staging area (index), Discard all changes.

```
git reset --hard HEAD~
```
4. Deletes a local branch named branch_name.

```
git branch -d branch_name

```
5. Force Delete a Branch (If Not Merged):

```
git branch -D branch_name

```
6. Delete a Remote Branch:

```
git push origin --delete branch_name

```
7. List both local & remote branches:

```
git branch -a

```
8. Prunes (removes) local references to remote branches that no longer exist on the remote.

```
git fetch --prune

```
9. Quickly Switch to the Previous Branch

```
git checkout -
```
10. Show a Visual Branch Tree

```
git log --oneline --graph --all
```
11. Search Commit Messages

```
git log --grep="bugfix"
```
12. Configures Git to use Windows' built-in SSL/TLS (Schannel) instead of OpenSSL

```
git config --global https.sslBackend schannel
```

















