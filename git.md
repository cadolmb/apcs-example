# Git

## One Time Setup

`git config --global user.name "Matthew Cadol"`
`git config --global user.email "link0833@gmail.com"`

## Project Setup

`git init`

## 3 Step Repeating Commit Process
1. Make Changes to code
2. Stage related changes
3. Commit changes with a message

## Commands

* status -> tell me what files have been staged or committed
* add -> add a file to the stage
* rm --cached -> remove file from stage
* git commit -m "Present tense description of what happened"
* git log -> Enter to move down, q to quit

## Problems
* commit without -m -> Use Esc :wq to quit Vim
* wrong message -> git commit --amend -m "New message"
