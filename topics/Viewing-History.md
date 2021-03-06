---
layout: bare
title: Topics • Viewing History
description: Viewing the history of commits.
---

# Log history
Show all history

    git log

Show all history as a series of patches

    git log -p

Show a week of history

    git log --since="one week ago"

Show the history of one file

    git log -- SOMEFILENAME

Show the number of lines modified (statistics)

    git log --stat

Show the diff (patch) of code changes from a specific commit

    git log trunk~259 -p
    git log HEAD^^^ -p

Show a finite range of commit messages

    git log HEAD~4..HEAD^1

## Showing Contents
Show the contents of the most recent commit in patch format

    git show

Show the contents of a arbitrary commit

    git show HEAD^^

## Describe
Short notation to refer to a commit based on its position relative to a branch point.

    git describe

