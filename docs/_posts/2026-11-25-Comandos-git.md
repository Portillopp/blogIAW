---
layout: post
title:  "Comandos Git!"
date:   2026-11-25 15:59:00 +0000
categories: git

---

# Comandos de Git

## Básicos

```bash
git init
git status
git add .
git add archivo.txt
git commit -m "mensaje"
git restore --staged archivo.txt
git rm --cached archivo.txt
```

## GitHub y repositorios remotos

```bash
git remote add origin <url>
git push -u origin <rama>
git push
git pull
```

## Ramas (branch)

```bash
git branch
git branch -a
git checkout -b nueva-rama
git switch -c nueva-rama
git checkout otra-rama
git switch otra-rama
git branch -m nuevo-nombre
git branch -d rama
git merge otra-rama
```

## Stash

```bash
git stash
git stash save "mensaje opcional"
git stash push -m "mensaje opcional"
git stash list
git stash apply
git stash pop
git stash drop stash@{0}
git stash clear
git stash -u
git stash -a
```
