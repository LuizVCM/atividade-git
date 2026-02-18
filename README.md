# Projeto pequeno, como atividade, para testar as funcionalidades básicas do git bash.]
Projeto:
--
AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents
## $ cd atividade-git

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (main)
## $ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        script.js

nothing added to commit but untracked files present (use "git add" to track)

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (main)
## $ git branch
* main

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (main)
## $ git branch "teste-branch"

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (main)
## $ git branch
* main
  teste-branch

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (main)
## $ git checkout teste-branch
Switched to branch 'teste-branch'

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (teste-branch)
## $ git add .

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (teste-branch)
## $ git status
On branch teste-branch
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   script.js


AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (teste-branch)
## $ git commit -m "Venho por esta mensagem informar que houve um arquivo de JavaScript adicionado"
[teste-branch 2c42c29] Venho por esta mensagem informar que houve um arquivo de JavaScript adicionado
 1 file changed, 5 insertions(+)
 create mode 100644 script.js

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (teste-branch)
## $ git status
On branch teste-branch
nothing to commit, working tree clean

AzureAD+LUIZVINICIUSCASSABON@SLE212046 MINGW64 ~/documents/atividade-git (teste-branch)
## $ git push origin teste-branch
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 450 bytes | 450.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'teste-branch' on GitHub by visiting:
remote:      https://github.com/LuizVCM/atividade-git/pull/new/teste-branch
remote:
To https://github.com/LuizVCM/atividade-git.git
 * [new branch]      teste-branch -> teste-branch

