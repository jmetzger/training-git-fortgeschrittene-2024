# Use pycharm as mergetool withing pycharm 

## Setup (Windows)

```
# Welche sind konfiguriert
git mergetool --tool-help
git config --global mergetool.pycharm.path "c/Program\ Files/JetBrains/PyCharm\ Community\ Edition\ 2024.2.4/bin/pycharm64.exe merge"
git config --global merge.tool meld
git config --global mergetool.keepBackup false
```
