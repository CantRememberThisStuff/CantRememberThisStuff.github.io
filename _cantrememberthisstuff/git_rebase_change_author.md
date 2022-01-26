---
description: |
  Change author info on older commits

  Command Reference:

    Nr Commits: The number of commits to change

    Author: (New) name of the author

    Email: (New) email

command: |
  git rebase -i HEAD~<nr_commits> -x "git commit --amend --author '<author> <<email>>' --no-edit"
  
items:

target: |
  - Linux_target
  - MacOS_target
  - Windows_target
  
OS:
  - Linux
  - MacOS
  
environment: |
  - Local
  
command_types:
  - Admin
  
references:
  - https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History
---
