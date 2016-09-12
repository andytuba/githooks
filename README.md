To enable these githooks on your repo, 

```
cd your_project
git clone ThisRepo.git .githooks
rm -rf .git/hooks && ln -s ../.githooks .git/hooks
```
