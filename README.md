# dotfiles

A collection of my dotfiles.

## Requirement

```bash
$ brew install chezmoi
```

## Basic Commands

```bash
# edit files
$ chezmoi edit

# stage files
$ git -- add ./
# or status
$ git -- status

# apply changes
$ chezmoi apply

# commit changes
$ chezmoi git -- commit -m "chore: update files"

# push changes
$ chezmoi git -- push
```
