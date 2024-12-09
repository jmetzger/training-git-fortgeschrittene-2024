# Dateien automatisch ignorieren (.gitignore) 

  * Bester Weg: Starte mit einer top-level .gitignore in der Du den kompletten .idea - Ordner hinzufügst

```
# .gitignore 
/.idea
```

  * Wichtig: .gitignore muss unbedingt am Anfang des Projekts geadded, committed und gepushed werden (falls man nicht mit einem Repo aus AWS Code Commit beginnt, sondern lokal)

## Hinweis 

  * Den Vorschlag von pycharm zu nehmen (der automatisch bei neuen Repos erstellt wird, ist suboptimal, weil hier Plugins, die man evtl. später verwendet / installiert nicht berücksichtigt werden. 
