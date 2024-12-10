# Special config settings 

## Conditional Include 

```
The path parts are relative, which means relative to the file that includes them (${HOME}\.gitconfig), rather than relative to the repository they operate on.
; relative paths are always relative to the including
; file (if the condition is true); their location is not
; affected by the condition
[includeIf "gitdir:/path/to/group/"]
        path = foo.inc

; include only if we are in a worktree where foo-branch is
; currently checked out
[includeIf "onbranch:foo-branch"]
        path = foo.inc
```

## Special settings for commit and merge 

```
commit.verbose=true: Shows the full diff being committed in the editor when writing a commit message.

merge.conflictStyle=diff3: Adds an extra section in merge conflicts that shows the code as it looked in the common ancestor commit. It can be difficult to figure out the correct result of a merge without this.
```
