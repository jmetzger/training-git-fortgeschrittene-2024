# git config

## How to delete an entry from config 

```
# Important: Find exact level, where it was added --global, --system, --local 
# test before
# should contain this entry 
git config --global --list 

git config --unset --global alias.log
```

## Set entry only for repo 

```
# Eintrag nur für repo setzen
git config user.name "mein-name-nur-fuer-repo" 
```
