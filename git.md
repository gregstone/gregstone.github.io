# PR : reviewx a PR in IDE 
**[REVIEW CHANGES IN IDE](https://medium.com/@mkutlev/pull-request-review-with-intellij-idea-or-android-studio-e60fbb3e3639)**

ex : 
* PR branch : feature_branch
* branch to merge to : develop

1. checkout develop 
2. git merge --no-commit --no-ff origin/feature_branch 
when review is finished : 
3. git reset --merge --hard