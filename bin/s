#!/bin/bash

## custom git status command


echo "Branch: $(gbc)"
echo "Origin: $(git remote -v | egrep "origin" | head -1 | sed 's/origin\s*//' | sed 's/(fetch)//')"
git status | grep -v "^On branch "
