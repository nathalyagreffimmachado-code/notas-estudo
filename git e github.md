# notas-estudo
tata`s version
markdown






 ## configurando git
 para ultilizar o git na maquina eu preciso configurar determinados comando,sendo eles:
 ```bash
 git config --global
 ```
 ## como configurar o github
 ## SSH - Como configurar a maquina para Github
 ## como criar um repositorio
 nesta aula aprendemos:
- instalar o git
- configurar o git
- criar conta no github
- configurar SSH no github
- instalar Nodejs
- instalar VScode
- criar repositorio
- clonar repositorio
- abrir VScode
## verificar se existe chave ssh
 ```bash
ls -al~/.ssh
```
## adicionar uma nova chave
```bash
ssh-keygen -t ed25519 -c"you_example.com"
```
## inicilizar agente-ssh
```bash
eval "$(ssh-agent -s)
```
## adicionar chave ssh ao agente.
```bash
ssh-add ~/.ssh/id_ed25519
```
## SSH-GITBash
## copiar chave ssh.
```bash
clip <~/.ssh/id_ed25519.pub
```
## adicionar chave no github
```bash
github ->Settings->SSH and gpg keys-> New SSH key- colar
```
## testar conexão
```bash
ssh -T git@github.com
yes
```
## VS Code - Extensões
```bash
Live server 
CSS peek
CSS Grid Snippets
Color highlight
dracuma theme official
```
## VS Code-Atalhos
```bash
! e html:5 para scaffoling rápido
Alt+L+O para visualizar HTML NO navegador
Ctrl+Space para sugestões de código
Ctrl+Shift+l para formatar código CSS
Ctrl+/para comentar linhas de codigo
Alt+Shift+F para formartar o código JavaScripy



github
nathalya62006496@JLE106D060774 MINGW64 ~
$ cd documents/

nathalya62006496@JLE106D060774 MINGW64 ~/documents
$ git clone git@github.com:nathalyagreffimmachado-code/Outrorepo.git
Cloning into 'Outrorepo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

nathalya62006496@JLE106D060774 MINGW64 ~/documents
$ cd Outrorepo/

nathalya62006496@JLE106D060774 MINGW64 ~/documents/Outrorepo (main)
