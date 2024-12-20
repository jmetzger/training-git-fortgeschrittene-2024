# GIT-Training für Fortgeschrittene 2024

## Agenda

  1. Geschichte / Grundlagen 
     * [GIT Pdf](http://schulung.t3isp.de/documents/pdfs/git/git-training.pdf)

  1. Cheatsheet / Spickzettel / cool stuff
     * [Git Cheatsheet](https://about.gitlab.com/images/press/git-cheat-sheet.pdf)
     * [Git cool commands](https://github.com/git-tips/tips?tab=readme-ov-file#list-all-the-conflicted-files)

  1. Best practices
     * [Best practices](best-practices.md)

  1. Basics - pycharm
     * [Put project under version control](pycharm/basics/01-put-project-under-version-control.md)
     * [Add unversionend files and commit](pycharm/basics/02b-add-files-to-repo-and-commit.md)
    
  1. Commit "rückgängig" machen
     * [Die letzte Commit-Nachricht ändern](pycharm/modify-commit/amend.md)
    
  1. Logs - pycharm
     * [Add commit-id to logs in pycharm](pycharm/logs/show-commit-id-in-logs.md)
     * [Show reflog](pycharm/logs/show-reflog.md)

  1. Interaction with Online (codecommit)
     * [Publish Project to codecommit](pycharm/online/create-repo-codecommit.md)   
  
  1. Tipps & Tricks - pycharm
     * [Which files to put under version control / which to ignore](pycharm/which-files-to-ignore-files.md)
     * [Disable ESC when using vi as editor](pycharm/disable-esc.md)
    
  1. Workflows
     * [git workflows](git-workflows.md)
    
  1. Background
     * [Why use tags](why-tags.md)
    
  1. Tipps & tricks 
     * [Beautified log](beautify-log.md)
     * [Datei aus altem commit bekommen](einzelne-datei-auschecken.md)
     * [Special config settings](config/settings.md)
    
  1. Kommandzeile (mit tipps & tricks) 
     * [git add + Tipps & Tricks](add.md)
     * [git commit](commit.md)
     * [git log](log.md)
     * [git config](config.md) 
     * [git show](show.md)
     * [Needed commands for starters](started-commands.md)
     * [git branch](branch.md)
     * [git checkout](checkout.md)
     * [git merge](merge.md)
     * [git tag](tag.md)
     * [git push/pull](push-pull.md)
     * [git reset](reset.md)
    
  1. Security
     * [Push Protection - scanning for hardcoded credentials](https://blog.gitguardian.com/github-push-protection-enhancing-open-source-security-with-limitations-to-consider/)
     * [Enable Push Protection](https://docs.github.com/en/code-security/secret-scanning/enabling-secret-scanning-features/enabling-push-protection-for-your-repository)
    
  1. hooks
     * [Git Hooks - Clientseitig](https://git-scm.com/book/de/v2/Git-einrichten-Git-Hooks)

## Backlog 
   
  1. Branches / Branching 
     * [Branch Overview with origin image](branches/overview.md)
   
  1. Advanced Commands 
     * [git reflog](reflog.md) 
     * [git reset - Back in Time](reset.md)   

  1. Tipps & Tricks 
     * [Change already committed files and message](commit-amend.md) 
     * [Best practice - Delete origin,tracking and local branch after pull request/merge request](best-practice-delete-branch.md)
     * [Einzelne Datei auschecken](einzelne-datei-auschecken.md)
     * [Always rebase on pull - setting](rebase-pull.md)
     * [Arbeit mit submodules](submodules.md) 
     * [Integration von Änderungen (commits, einzelne Dateien) aus anderen commits in den Master](integrate-to-master.md)
     * [Fix conflict you have in merge-request (gitlab)](fix-conflict-merge-request.md) 
     * [SETUP.sql zu setup.sql in Windows (Groß- und Kleinschreibung)](setup-SETUP_sql.md)
     * [Force specfic commit message](pre-receive-hook.md)
     * [Alle Dateien, die sich geändert haben anzeigen z.B. heute](files-changed-today.md)
  
  1. Exercises 
     * [merge feature/4712 - conflict](merge-conflict.md)
     * [merge request with bitbucket](merge-request.md)
  
  1. Snippets 
     * [publish lokal repo to server - bitbucket](local-public.md)
     * [failure-on-push-fix](failure-push.md)
     * [failure-on-push-with-conflict](failure-push-conflict.md)
     
  1. Extras 
     * [Best practices](bp.md) 
     * [Using a mergetool to solve conflicts](mergetools.md)
  
  1. Help
     * [Help from commandline](help.md)
   
  1. submodules
     * [submodules](submodules.md)
   
  1. Authentication 
     * [Work with different credentials](credential-helper.md)
     
  1. Shells 
     * [color for zsh-shell under osx](https://gist.github.com/chrisnolet/d3582cd63eb3d7b4fcb4d5975fd91d04)
     * [branch mit anzeigen in zsh-shell und osx](https://github.com/romkatv/powerlevel10k)
   
  1. Documentation 
     * [GIT Pdf](http://schulung.t3isp.de/documents/pdfs/git/git-training.pdf) 
     * [GIT Book EN](https://git-scm.com/book/en/v2)
     * [GIT Book DE](https://git-scm.com/book/de/v2)
     * [GIT Book - submodules](https://git-scm.com/book/de/v2/Git-Tools-Submodule)
     * [GIT Guis](https://git-scm.com/downloads/guis/)
     * [Third Party Tools](tooling.md)
     * [Specification Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
     * https://www.innoq.com/de/talks/2019/05/commit-message-101/
     * https://github.com/GitAlias/gitalias/blob/main/gitalias.txt
     * https://education.github.com/git-cheat-sheet-education.pdf
     * [.gitignore](https://git-scm.com/docs/gitignore)
     * [learn branching](https://learngitbranching.js.org/?locale=de_DE)
     
  1. Datenbank - Versionierung 
     * [Methode 1](https://github.com/sergiosbx/pyway)
     * [Methode 2](https://flywaydb.org/) 

  1. Installation 
     * [GIT auf Ubuntu/Debian installieren](installation-ubuntu-debian.md)
     * [GIT unter Windows installieren](https://git-scm.com/download/win)
    
  1. Tipps & Tricks (Aufräumen) 
     * [Tracking Branches (shadow branches) nach Integration Online löschen](remote-branches-delete.md)
  
  1. Tipps & Tricks (editor) 
     * [Notepad als Editor verwenden- Windows](notepad-git.md)
     * [TextEdit als Editor unter mac verwenden](textedit-git.md)
 
