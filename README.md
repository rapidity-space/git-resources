# Git Resources
Commonly used commands, cheat sheets, tools, etc.

## Introduction
Version control with git. Why? How? What else? 

## Model
```mermaid
  flowchart LR;
      working_dir-->|git add|staged;
      staged-->|git rm|working_dir;
      staged-->|git commit|local;
      local-->|git push|remote;
      remote-->|git pull|local;
```


## Commands
- ```git clone <repo>``` creates a local clone of an existing remote repository.
- ```git add <file>``` stages an existing file for commit.  
- ```git commit -m <message>``` cerate a local commit of staged files.
- ```git commit``` create a local commit of staged files with a message interactively written in an editor.
- ```git pull``` pulls new commits from the remote repository to the local repository.
- ```git push``` pushes local commits to the remote repository.

## Branches
...

## Cheat Sheets
[Cheat Sheet #1](https://images.datacamp.com/image/upload/v1656573882/Marketing/Blog/git_cheat_sheet.pdf)

## Github
A host for remote git repositories which provides numerous additional features/services

### Getting Started
1. Create account.
2. Create organization.
3. Create repositories.
4. Set up SSH keys allow push to remote repo.
   
### Editing
[Github markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
[Mermaid diagram intro](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
[Mermaid diagram syntax](https://mermaid.js.org/intro/syntax-reference.html)

### Github Actions
Github Actions is Github's CI/CD system which can be used for building, testing, and deploying software, but also for other automation tasks. 
[Quick Start](https://docs.github.com/en/actions/quickstart)
[Workflows](https://docs.github.com/en/actions/using-workflows)


