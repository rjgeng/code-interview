---
layout: default
---

# Code signal Arcade

```
rm -rf interview-arcade
rm .gitmodules
rm -rf .git
git init
git branch -M gh-pages
git remote add origin https://github.com/rjgeng/interview.git
git submodule add git@github.com:freeCodeChallenges/interview-arcade.git
git add .
git commit -m 'first commit'
git push origin gh-pages --force
```
