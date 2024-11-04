# Best practices 

## Repos anlegen 

 * Kein git init sondern Versionsverwaltung über pycharm

## Commits 

 * Zeile 1: 50 Zeichen
 * Bestehend aus [Ticket-ID oder Modul/Bereich] Kurztitel
 * Sollte so sein, dass die Kollegen das verstehen
 * Evtl. ab Zeile 3 weitere Bemerkungen (eher selten) 

### Wie oft ?

  * Häufig committen, wenig pushen (z.B durchaus 10-15 commits und 1-2 pushen)

## Branches 

### Allgemein 

  * Nicht zuviele Unterbranches erstellen
    * nur eine Ebene feature-branches
  * Alle Branches, die integriert worden sind, löschen (Feng Shui)

### Thema: no-ff 

  * Besser: no-ff als fast-forward (wird aber online ohnehin automatisch gemacht)
    * Warum: Damit wir sehen, was in ein Feature integriert wurde (welche commits)
 
### Wann ? 

  * Immer Branches verwenden, wenn mehr als 2 Leute im Team

### Benamung ?

   * feature/xxxx - wobei xxxx (Ticket-Id oder Kurzbezeichnung) ist 

## Reset / amend (kommandos, die die Historie verändern

  * Nicht mehr für commits machen, die veröffentlicht wurden (ge-pushed zum Server)
